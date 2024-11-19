##############################################################################################################
NGS 기초
    1. 생물정보 입문을 위한 NGS 기초 이론과 용어 설명
        NGS 정의 및 전반의 이론 확립
        NGS 데이터 분석 실무를 위한 용어 정복
    2. 교육의 특징
        NGS 정의 및 플랫폼의 이해, 응용 연구 분야 소개
##############################################################################################################
제 1강 NGS 정의 및 개요
    시퀀실 발전 과정과 NGS 개요
제 2강 Sanger vs. NGS
    Sanger 시퀀싱 방법과 NGS 시퀀싱의 비교
제 3강 NGS 플랫폼의 이해 - Illumina, ThermoFisher
    Illumina NGS 플랫폼의 특징 이해
    ThermoFisher NGS 플랫폼의 특징 이해
제 4강 NGS 플랫폼의 이해 - PacBio, Nanopore
    PacBio NGS 플랫폼의 특징 이해
    Oxford Nanopore NGS 플랫폼의 특징 이해
제 5강 NGS 응용 연구분야 소개
    NGS를 활용한 응용 연구분야 소개
##############################################################################################################
제 1강 NGS 정의 및 개요
    Sequencing Evolution / Revolution
        Human Genome Project
        The History of DNA Sequencing Technology
        Back to the Genomic Era
        Human Genome Sequence cost
        What is NGS
            차세대 염기서열 분석(Next Generation Sequencing, NGS)은 하나의 유전체를 무수히 많은 조각으로 분해하여,
            각 조각을 동시에 읽어낸 뒤, 생물정보학 기법을 이용하여 조합함으로써 방대한 유전체 정보를 빠르게 해독하는 방법
            전통적인 Sanger sequencing처럼 한 번에 한 개씩이 아니라 많은 DNA 가닥의 시퀀싱을 동시에 가능하게 했음
            - 초기에는 "대량 병렬 시퀀싱(massively-parallel sequencing)"이라고 불렸음
            2006년 처음 상용화되어, 10년도 안 되는 기간 동안 유전체 연구의 혁명을 가져왔다
            Roche - GS FLX
            Illumina - Genome Analyzer
            ABI - SOLID
        Developments in high throughput sequencing
        Comparison of NGS platform
        Sequencing as a Powerful Methodology
        NGS application
##############################################################################################################
제 2강 Sanger vs. NGS
    DNA 시퀀싱의 역사
    DNA 합성 과정
    Sanger 염기서열 분석법의 원리
        Sanger 시퀀싱이란?
        Sanger 시퀀싱의 장/단점
        Sanger와 NGS의 비교
        Sanger vs NGS 상황별 선택
##############################################################################################################
제 3강 NGS 플랫폼의 이해 - Illumina, ThermoFisher
    Comparison of NGS platform
    The beginning of the NGS era
        Roche - GS FLX
        Illumina - Genome Analyzer
        ABI - SOLID

    Illumina sequencing platform
        Cluster generation
        Sequencing by synthesis(SBS)
        A. Library Preparation
        B. Cluster Amplification
        C. Sequencing
        D. Alignment and Data Analysis
        Paired-End / Mate Pair Sequencing
        Applications

    ThermoFisher Ion Torrent
        Ion Torrent sequencing Platforms
        Ion Torrent 반도체 시퀀싱 원리
            분석 할 DNA를 적당한 크기로 나누고, DNA의 양 말단에 증폭에 필요한 프라이머 결합 염기서열을 결합하여
            라이브러리 제작
            라이브러리 분자들은 에멀젼 PCR(emulsion PCR) 방법을 통해 DNA를 비드 표면에서 증폭하여 사용되며
            한 개의 비드에는 한 가지 단일분자가 복제 증폭된 DNA가 결합
            합성 시 3번 탄소에 결합된 -OH기에서 산소분자는 phosphodiester bond 결합에 사용되고
            수소분자는 DNA가 합성된 이후에 방출됨
            방출된 수소분자는 반도체칩 위에 올려진 센서에 의해 탐지되고 A,T,G,C 합성에 의한 전기신호를 판별하여
            염기서열을 알 수 있음
                동일한 염기서열이 반복해서 존재하는 경우 한번 반응에 다수의 동일한 염기가 합성되고
                이에 비례하여 높은 전기적 신호가 나타남.
        Homopolymer Error
        Applications
##############################################################################################################
제 4강 NGS 플랫폼의 이해 - PacBio, Nanopore
    3rd Generation Sequencing Platform
        PacBio SMRT
        Oxford Nanopore
    세대별 시퀀싱 기술 비교
    Long-read 시퀀싱의 특징
    PacBio
        PacBio sequencing platforms
            RS / Sequel
        PacBio 시퀀싱 기술의 원리 - SMRT
            Single Molecule Real Time sequencing(SMRT)
            레이저가 형광 측정
        두가지의 시퀀싱 모드
            Circular Consensus Sequencing(CCS) mode
            Continuous Long Read(CLR) mode
        Hi-Fi Read
        Applications
    Oxford Nanopore
        Oxford Nanopore Platform
        Nanopore
        Nanopore sequencing
            전압의 변화에 따라 DNA 서열을 알 수 있음
##############################################################################################################
제 5강 NGS 응용 연구분야 소개
    Part 1. 유전체 분석
        Step 1. NGS design & Sequencing
            Sequencing design - example
                대상 유전체의 생물학적 특성 이해를 기반한 시퀀싱 실험 디자인
                NGS Machine의 특징을 활용한 실험 디자인
                NGS와 계층적 샷건(hierarchical shot-gun sequencing)법의 조화를 이뤄야 함
                시작부터 Finishing 단계를 고려한 실험설계가 필요함
        Step 2. De novo assembly
            What is an Assembly
                De-novo / Reference assembly
            NGS assembler
            The challenge of assembly
            Strategy of de novo assembly
        Step 3. Structural annotation
            Gene structure
            Gene modeling
            Gene statistics - example
        Step 4. Functional annotation
            Gene functional category
            Comparative genomics
    Part 2. 유전체 변이 분석
        Overview of SNP
        Classification of SNP by location
        Substitution
        Genetic variations : SNPs & InDels
        The HapMap Project
        1000 Genomes Project
        SNP chip
        The SNP-In-Primer Problem
        Target sequencing (Capture array)
        Exome sequencing
        Analysis Strategy of SNP study
        Differences variant callers
        SNP discovery : Goal
        GWAS(Genome wide association study)
    Part 3. 전사체 분석
        What is Transcriptomics
        RNA sequencing
        Why sequence RNA (versus DNA)
        Step 1 : NGS sequencing
        Step 2 : Preprocessing
        Step 3 : Mapping
        Step 4 : Estimate expression abundance
        Step 5 : DEG selection
        Step 6 : Functional annotation
    Part 4. 후성유전체 분석
        What is the epigenome
        Epigenetics
        Gene regulation
        Epigenetics and Aging
        Epigenomics
        Epigenomics using NGS
        ChIP-seq
        Analysis of ChIP-seq data
    Part 5. 환경유전체 분석
        The role of bioinformatics in microbiology
        Metagenomics
        Era of Metagenomics by sequencing
        16s targeted vs. Whole metagenome
        2 Kinds of Microbiome study - 16S rRNA and Whole-genome shotgun
        Metagenomics Workflow
        Metagenomic sequence analysis tools
        Metagenome analysis result - Microbial Genomics Module example
        Alpha Diversity
        Beta Diversity
##############################################################################################################
##############################################################################################################
#
KGOL_유전체분석기초이론(2020)
    1. 유전체 분석 입문을 위한 기초 이론과 용어 설명
        유전체 분석 전반의 워크플로우 및 이론 확립
        유전체 분석 실무를 위한 용어 정복
    2. 교육의 특징
        유전체 분석의 단계별 개념 이해
#
제 1강 Genome Project 개요
    NGS와 유전체 분석 기술의 발전과정
    유전체 분석 현황
제 2강 Whole Genome Sequencing
    전장 유전체 분석을 위한 NGS 시퀀싱
제 3강 De novo assembly
    De novo assembly 개념 이해
제 4강 Structural annotation
    Gene prediction 방법 및 개념 이해
제 5강 Functional annotation
    유전자 기능 분석을 위한 데이터베이스 소개
#
제 1강 Genome Project 개요
    Human Genome Project
    Eukaryotic Genome Annotation
    Genome Project
    The History of DNA Sequencing Technology
    Back to the Genome Era.
    Human Genome Sequence cost
    What is NGS?
    Developments in high throughput sequencing
    Comparison of NGS platform
    Sequencing as a Powerful Methodology
    NGS application
        DNA Level
        # variations
            Whole genome resequencing(WGRS)
                Discover the genetic variations in a genome-wide range
            Exome Seq
                Discover the causative, susceptibility loci
                Discover rare/novel variants
                More economical and efficient
            Target Region Seq
                Find the novel variants or validate the candidate variants in the target regions
            Genotyping
                SNP and CNV detection in a genome-wide range
                Customized array for personal usage which is more flexible
                Validation of candidate pathogenetic genes or loci in large amount of samples
            Single Cell Seq
                Genetic variation research at single cell level
                Explore cancer cells evolution during tumor progression
        RNA Level
            Transcriptome Seq
                Comprehensive of differential gene expression
                Discover novel genes
                RNA editing analysis(such as alternative splicing, cSNP, gene fusion, etc)
            RNA-Seq (Quantification)
                Precise quantification of gene expression analysis that is suitable for large samples
                Discover disease-related functional genes
            Small RNA Seq
                Gene expression analysis of miRNA
                Gene regulatory networks and targets study of miRNA
                Discovery disease-specific biomarkers
            Non-coding RNA Seq
                Identify novel non-coding RNA
                Discover disease-specific biomarkers
            Cell Line Seq
                Obtain a clear and comprehensive genetic patterns of the cell lines
                Obtain mutation information of high accuracy
        Epigenetic Level
            Whole Genome Bisulfite Seq(WGBS)
                DNA methylation research at whole genome-wide level
                High accuracy and high resolution(single-based)
            MeDIP Seq
                Based on immunoprecipitation for methylated DNA enrichment
                Whole genome-wide DNA methylation research and cost-effective
            RRBS Seq
                Methylation analysis of promoter regions with substantial genome coverage
                Based on enzyme digestion and bisulfite treatment
                Good repeatability
            ChIP Seq
                Genome-wide protein-DNA interaction studies
                Higher resolution, more precise and abundant than ChIP-chip
        Protein Level
            Proteome Profiling
                Analyze the component of protein mixtures
                Obtain comprehensive information of protein category, metabolic pathways, etc
            Quantitative Proteomics
                Fast and accurate protein differential analysis for multiple samples
            Modification Proteomics
                Fast and comprehensive analysis of protein modification spectrum for multiple samples
            Target Proteomics
                Based on the technology of Multiple Reaction Monitoring(MRM)
                Validate the discovered biomarkers
                Identify protein modification and low abundant proteins
        Genome
            de novo sequencing : assembly - annotation
            resequencing : mapping - detection of SNPs/indels/other variants
            phylogeny/evolution/ecology/individual genetic differences
                gene content/non-coding regions
                biochemical potential
                phylogenetic trees
                horizontal gene transfer
                environmental distribution (metagenomics)
                biodiversity (metagenomics)
                genome variability (SNPs, indels, structural variants)
                association studies/QTL analysis
                detection of mutations
                1000 genome projects
        Chromatin
            Hi-C : mapping - 3D reconstruction
            ChIP-Seq : mapping - detection of binding sites
            genome organization
                3D genome architecture
                interactoins between nucleic acids and proteins
        Transcriptome
            ChIP-seq : mapping - detection of binding sites
            RNA-Seq : mapping  - splice site detection/transcript assembly - quantification
            genome activity
                interactions between nucleic acids and proteins
                transcript abundance
                co-regulated pathways
                co-regulated gene cluster
                molecular phenotypes
#
제 2강 Whole Genome Sequencing
    Workflow
        Design - Sequencing - De novo assembly - Structural annotation - Functional annotation
        Paired-end / Mate-pair / PacBio
            (>100X)
    Sequencing design
        대상 유전체의 생물학적 특성 이해를 기반한 시퀀싱 실험 디자인
        NGS Machine의 특징을 활용한 실험 디자인
        NGS와 계층적 샷건(hierarchical shot-gun sequencing)법의 조화를 이뤄야 함
        시작부터 Finishing 단계를 고려한 실험설계가 필요함
    Human Genome Sequencing
    Genome Sequencing
    Strategies for Whole Genome Sequencing
        1. Hierarchical - Clone-by-clone
            i. Break genome into many long pieces
            ii. Map each long piece onto the genome
            iii. Sequence each piece with shotgun
            Example : Yeast, Worm, Human, Rat
        2. Online version of (1) - Walking
            i. Break genome into many long pieces
            ii. Start sequencing each piece with shotgun
            iii. Construct map as you go
            Example : Rice genome
        3. Whole genome shotgun
            One large shotgun pass on the whole genome
            Example : Drosophila, Human(Celera), Neurospora, Mouse, Rat, Fugu
        A. BAC by BAC sequencing strategy
        B. De novo assembly using short or long reads
    Draft vs. Finishied genome
        De novo assemble your reads into contigs
            Unique chunks of contiguous DNA
        Join contigs into scaffolds
            Only if you have paired or strobed reads
            Scaffolds contain gaps of ambiguous Ns
        Close gaps
            Design primers around gaps
            Sequence the resultant PCR product
        Validate
            Align your reads back onto the draft genome
            Check against optical maps(up to 100MBp)
        Shotgun sequencing
            Single-end
            Paired-end
            Mate-pair
        Genome assembly
            Contigs
            Scaffold
        Annotation
            Related genome
            Annotated draft genome
            RNA-seq data
    DNA sequencing
    NGS platform
    Sequencing design - example
    Strategies for Long-Read Sequencing and De Novo Assembly
    Genome size의 다양성
    Genome size 예측 방법
        A. 실험적인 기술
            Feulgen densitometry (유전체 크기 예측)
            Flow cytometry (유전체 크기 예측)
            C0t Analysis (DNA reassociation kinetics) : 반복서열 측정 및 분류
            molecular markers or DNA microarrays : heterozygosity 정도 측정
        B. 분석적인 기술 (K-mer frequency)
            Mixed-Poisson Model and EM algorithm : 2003년 Michael S. Waterman 그룹
            (문제점, 데이터가 완벽해야 하고, 다른 많은 한계를 가짐, 또한 Tool 제공을 하지 않았음)
            GSP (genome size prediction) Bayesian estimation (BE) and EM iteration:
            2009년 Shan & Zheng (일부 염기 서열 오류를 허용)
    k-mer frequency distribution 측정
        jellyfish
        17-21 mer
    RNA-seq을 활용한 genome 예측
#
제 3강 De novo assembly
