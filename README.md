# bioinformatics-capstone--Alaya-Lopez- # Project Title

Salmonella Genome Assembly Evaluation 

## Description

The project focuses on assessing the quality of Salmonella genome assemblies. Genome assemblies can vary in completeness, contiguity, and potential contamination, which affects research outcomes. By using QUAST, we can quickly evaluate key assembly metrics such as N50, total number of contigs, and total assembly length. This is useful for ensuring high-quality genomes are used in further analyses, like phylogenetics, gene annotation, or comparative genomics.

## Getting Started

### Prerequisites


- QUAST-genome assembly evaluation tool 
- Python 3.8+- for QUAST dependencies 
- Git- to clone the repository 

### Installation

# Clone the repository
git clone https://github.com/yourusername/salmonella_assembly.git
cd salmonella_assembly

# (Optional) Create a virtual environment
python3 -m venv venv
source venv/bin/activate

# Install QUAST (if not already installed)
# Option 1: Using Conda
conda install -c bioconda quast

# Option 2: From source
# Download from http://quast.sourceforge.net/

```bash
git clone https://github.com/yourusername/yourproject.git
cd yourproject
npm install
