rule all:
    input:
        "results/output.txt"
rule echo_text:
    input:
        "data/text.txt"
    output:
        "results/output.txt"
    shell:
        """
        mkdir -p results
        echo "File content:" > {output}
        echo "$(cat {input})" >> {output}
        """
