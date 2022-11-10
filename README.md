# bh22
notes on bh22

### VGP Assembly training short form:

Get data

A. check data is available: Shared Data -> Histories -> VGP assembly tutorial data  <Click name>
B. Data view: 7. 3. 2. 1. showing HIFI collection, Bionano Dataset, HI C data set R and Hi C dataset F 
C. Press Import  to right upper of screen

Import workflows from WorkflowHub
  Hands-on: Import a workflow

        Click on the Workflow menu, located in the top bar. Workflow menu.
        Click on the Import button, located in the right corner.
        In the section Import a Workflow from Configured GA4GH Tool Registry Servers (e.g. Dockstore), click on Search form.
        In the TRS Server: workflowhub.eu menu you should type name:vgp
        
        THE DISPLAYED LIST DOES NOT INCLUDE THE WORKFLOW FOR THIS EXCERCISE: https://training.galaxyproject.org/training-material/topics/assembly/tutorials/vgp_workflow_training/workflows/
        Link from supporting matierials workflow is ok: VGP assembly tutorial data
        
        and then does run workflow make sense?  ( if can get to workflow will be ok)
        need to get to workflow and press run.
         
         next genome profile analysis ?? cant figure this out?
         
         But if I just run the workflow everything starts at once.... 
         
         So it appears there should be multiple workflow for each step, and the assembly workflow runs all steps..
         
         
         
         Grace work:
         https://colab.research.google.com/drive/1ClrRX_0ZK3Pvz52vegVbKHXnb4mEQ3gq?usp=sharing#scrollTo=v7GnaZtb0F9S
         
         Project 6 update:
         ![Project6Update](https://user-images.githubusercontent.com/38674063/200831991-af9ab57a-4bca-4871-807f-6f6a26d9f80e.png)
         
ZEBRA FINCH DATA :zebra_face: :bird:

    hifi FASTQ.GZs here: https://genomeark.s3.amazonaws.com/index.html?prefix=species/Taeniopygia_guttata/bTaeGut2/genomic_data/pacbio_hifi/
    bionano CMAP (the DLE1 one) here: https://genomeark.s3.amazonaws.com/index.html?prefix=species/Taeniopygia_guttata/bTaeGut2/genomic_data/bionano/
    the arima reads are over many lanes so just use the concatenated files here: https://genomeark.s3.amazonaws.com/index.html?prefix=working/

    bTaeGut2_r1.fastqsanger.gz
    r2.fastqsanger.gz
    
    https://github.com/Delphine-L/iwc/tree/VGP/workflows/VGP-assembly-v2/VGP-HiC-Yahs workflow
    
    
[20220-11-08_tools_needed_in_Galaxy_by_Heidrun.odt](https://github.com/jo-mc/bh22/files/9971083/20220-11-08_tools_needed_in_Galaxy_by_Heidrun.odt)

ROLES (please ping me if you want me to edit this!)

    tool/conda wrapping

    Cameron (BandageNG), Anthony (FCS, maybe), Loraine (nextdenovo, ratatosk), Tyler (geneid), Linelle (fastk, or goldrush wrapper if i get frustrated)

    annotation

    Sagane, Tyler, Jèssica, Heidrun, Anthony (existing annotation workflow?), Loraine, Dima

    ONT assembly

    Tyler, Jèssica, Nando, Nadège
    Diego (early testing)

    general assembly

    Nadège, Diego, Giulio
    Australia team generally: getting VGP workflow/tools onto Galaxy AU :flag-au: 

    evaluation

    Giulio (MultiQC integration), Diego (QC in Galaxy)

TEST DATA :sponge: :petri_dish:

    sponge (ERGA; ONT, illumina, arima) https://ergapilot.bsc.es/index.php/apps/files/?dir=/ERGAPilot/species/Phakellia_ventilabrum&fileid=217541
    yeast (ERGA; ONT) https://usegalaxy.eu/libraries/folders/Ff10fa8e955fcc8a7/page/1
    zebra finch (VGP; hifi, illumina, bionano, arima) https://biohackeu.slack.com/archives/C03HC45TLFM/p1667982700664519
    
    Review of all projects:
    http://preview.biohackrxiv.org/
    
    
    machine learning onnx format
    
    Project 14 ontologies to map to user vocabulary
    
    easybuild/EESSI 16
    https://www.eessi-hpc.org/
    
    MOWL ontology of ML 18
    
    nightingale web components  19
    
    ebi-webcomponents.github.io/nightingale/2022
    
    20 federated EGA nodes - bash ?
    
    Hi, this is the URL for annotation of group 24. We really really need your help with this to create an open dataset on sex bias in biology research. The website is on but not working. https://cirillodavide-sentence-curation-streamlit-app-rzri06.streamlit.app/
    
    Project 34 public data -> predicting effective treatments
