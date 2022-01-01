# EditEx: Automatic Prediction of Rejected Edits in Stack Overflow

**Abstract:** The content quality of shared knowledge in Stack Overflow (SO) is important to support software developers with their programming problems. SO allows its users to suggest edits to improve the quality of a post (i.e., answer and question). However, existing research shows that many suggested edits in SO are rejected due to undesired contents/formats or for violating edit guidelines. Such a scenario could frustrate/demotivate users, who would like to provide good quality edits. Our research focuses on supporting SO users by offering them guidance on how to improve their editing of posts. First, we manually investigate 764 (382 questions + 382 answers) rejected edits and produce a catalogue of 17 rejection reasons. Second, we extract 14 texts and user-based features to capture those rejection reasons. Third, we develop machine learning models using those features. Our model can predict rejected edits with 79.2% precision, 68.1% recall, 69.6% F1-score and 70.4% overall accuracy. Fourth, we introduce an online tool named EditEx that works with the SO edit system as follows. EditEx can guide users during their editing of posts by suggesting the potential causes of rejection. According to our experiment, EditEx can support SO standard edit system to prevent 49% rejections. Participants who use EditEx to suggest edits find the potential rejection reasons identified by EditEx influential. Furthermore, the median workload suggesting edits using EditEx is half compared to the SO edit system.

## Accepted protocol

    Saikat Mondal, Gias Uddin, and Chanchal K. Roy. "Automatic Identification of Rollback 
    Edit with Reasons in Stack Overflow Q&A Site." IEEE International Conference on Software 
    Maintenance and Evolution (ICSME). IEEE, 2020.

**Download this paper:** [PDF](https://osf.io/sjgnz)

## Materials included in the ***Replication Package*** folder

### Manually Analyzed Dataset **/Replication Package/Manually Analyzed Dataset/`** 

* `ManuallyAnalyzedDataset.csv` contains our manually investigated dataset.
