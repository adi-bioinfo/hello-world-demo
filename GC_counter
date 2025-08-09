def gc_content(dna_seq):
    dna_seq = dna_seq.upper()
    g = dna_seq.count("G")
    c = dna_seq.count("C")
    gc_percentage = (g + c) / len(dna_seq) * 100
    return round(gc_percentage, 2)

# Example usage
sequence = "ATGCGCGTAATAGC"
print(f"GC Content: {gc_content(sequence)}%")
