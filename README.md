# Random-DNA-Sequence-Generator-in-R
This repository contains an R script designed to generate random DNA sequences of any specified length. DNA sequences are composed of four nucleotide bases: adenine (A), thymine (T), cytosine (C), and guanine (G). This script simulates random sequences by sampling these bases, making it a simple yet useful tool for various applications 

# Function to generate random DNA sequence
``generate_random_dna <- function(length) {
  bases <- c("A", "T", "C", "G") `` # DNA bases
  
 `` paste(sample(bases, length, replace = TRUE), collapse = "")
}``

# Example: Generate a random DNA sequence of length 50
``set.seed(123) `` # Set seed for reproducibility (optional)

``random_dna_sequence <- generate_random_dna(50)``

``cat("Random DNA Sequence: ", random_dna_sequence, "\n")``
