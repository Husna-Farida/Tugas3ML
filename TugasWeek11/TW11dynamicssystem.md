```mermaid
flowchart TB
    A[Limbah Biomassa Domestik] -->|"dibakar dalam"| B[Insinerator Skala Kecil]
    B -->|"menghasilkan"| C[Emisi CO₂ dan NOx]
    C -->|"meningkatkan"| D[Dampak Lingkungan]
    D -->|"menurunkan"| E[Kualitas Udara & Kesehatan Masyarakat]

    C -->|"meningkatkan"| F[Kebutuhan Teknologi Pengendalian Emisi]
    F -->|"mendorong"| G[Penerapan Air Staging]
    G -->|"mengubah"| H[Distribusi Udara Pembakaran]
    H -->|"mengurangi"| C

    G -->|"berpengaruh pada"| I[Efisiensi Pembakaran]
    I -->|"berdampak pada"| J[Produksi Emisi Tambahan Karbon Monoksida]

    K[Karakteristik Bahan Bakar] -->|"mempengaruhi"| C
    K -->|"mempengaruhi"| I

    %% Styling: class definition
    classDef cause fill:#fff2cc,stroke:#000,color:#000;
    classDef effect fill:#fce4ec,stroke:#000,color:#000;
    classDef solution fill:#e1f5fe,stroke:#000,color:#000;

    %% Assign class
    class A,B,K cause;
    class C,D,E,J effect;
    class F,G,H,I solution;
