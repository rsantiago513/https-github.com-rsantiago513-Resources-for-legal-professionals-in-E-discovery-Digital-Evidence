# E-Discovery and Digital Evidence Resources for Legal Professionals 

Electronic discovery (E-Discovery) refers to discovery in legal proceedings such as litigation, government investigations, or Freedom of Information Act requests, where the information sought is in electronic format often referred to as electronically stored information. Electronic discovery is subject to rules of civil procedure and agreed-upon processes, often involving review for privilege and relevance before data are turned over to the requesting party. Electronic information is considered different from paper information because of its intangible form, volume, transience and persistence. Electronic information is usually accompanied by metadata that is not found in paper documents and that can play an important part as evidence, for example, the date and time a document was written could be useful in a copyright case. The preservation of metadata from electronic documents creates special challenges to prevent spoliation.

Computer forensics is its own brand of forensics using investigative processes to collect, analyze and present digital evidence for legal proceedings. Sometimes called ''cyber forensics,'' these digital and computer-based techniques can often provide the evidence necessary to solve a crime. Computer forensics experts use a variety of software and other applications to retrieve, identify and extract data, even data that has been hidden or deleted, and then offer their report or interpretation of the data collected. Digital evidence on computers can be challenging to work with. While some of it may be visible, a good portion of a computer forensic expert's work is involved in discovering latent or hidden data inside a computer's systems. Whether out in the open or hidden, the process of computer forensics is the same: collect, analyze and present the digital data discovered.

## The Electronic Discovery Refernce Model (EDRM) 

The EDRM diagram represents a conceptual view of the E-Discovery process, not a literal, linear or waterfall model. One may engage in some but not all of the steps outlined in the diagram, or one may elect to carry out the steps in a different order than shown here. The diagram also portrays an iterative process. One might repeat the same step numerous times, honing in on a more precise set of results. One might also cycle back to earlier steps, refining one’s approach as a better understanding of the data emerges or as the nature of the matter changes. The diagram is intended as a basis for discussion and analysis, not as a prescription for the one and only right way to approach E-Discovery.

These are the stages:
  
  1. *Identification* - The identification phase is when potentially responsive documents are identified for further analysis and review. This created the idea of legal holds, eDiscovery, and electronic preservation. Custodians who are in possession of potentially relevant information or documents are identified. To ensure a complete identification of data sources, data mapping techniques are often employed. Since the scope of data can be overwhelming in this phase, attempts are made to reduce the overall scope during this phase, such as limiting the identification of documents to a certain date range or search term(s) to avoid an overly burdensome request.
  2. *Preservation* - A duty to preserve begins upon the reasonable anticipation of litigation. During preservation, data identified as potentially relevant is placed in a legal hold. This ensures that data cannot be destroyed. Care is taken to ensure this process is defensible, while the end goal is to reduce the possibility of data spoliation or destruction. Failure to preserve can lead to sanctions. Even if the court ruled the failure to preserve as negligence, they can force the accused to pay fines if the lost data puts the defense at an undue disadvantage in establishing their defense.
  3. *Collection* - Once documents have been preserved, collection can begin. Collection is the transfer of data from a company to their legal counsel, who will determine relevance and disposition of data. Some companies that deal with frequent litigation have software in place to quickly place legal holds on certain custodians when an event, such as legal notice, is triggered and begin the collection process immediately. Other companies may need to call in a digital forensics expert to prevent the spoliation of data. The size and scale of this collection is determined by the identification phase.
  4. *Processing* - During the processing phase, native files are prepared to be loaded into a document review platform. Often, this phase also involves the extraction of text and metadata from the native files. Various data culling techniques are employed during this phase, such as deduplication and de-NISTing. Sometimes native files will be converted to a petrified, paper, like format (such as PDF or TIFF) at this stage, to allow for easier redaction and bates-labeling. Modern processing tools can also employ advanced analytic tools to help document review attorneys more accurately identify potentially relevant documents.
  5. *Review* - During the review phase, documents are reviewed for responsiveness to discovery requests and for privilege. Different document review platforms can assist in many tasks related to this process, including the rapid identification of potentially relevant documents, and the culling of documents according to various criteria (such as keyword, date range, etc.). Most review tools also make it easy for large groups of document review attorneys to work on cases, featuring collaborative tools and batches to speed up the review process and eliminate work duplication.
  6. *Production* - Documents are turned over to opposing counsel, based on agreed-upon specifications. Often this production is accompanied by a load file, which is used to load documents into a document review platform. Documents can be produced either as native files, or in a petrified format (such as PDF or TIFF), alongside metadata.


## E-Discovery and Digital Evidence Tools 

E-Discovery can be a complicated and overwhelming task. Data evidence must not only be collected, but also be acquired in a manner that validates the data's authentication in court. Specialized software tools are available that help with collecting, sorting, and producing relevant data. Although digital forensics tools and E-Discovery tools have manny common features, they are designed for different purposes. Digital forensics tools are designed to collect data in a manner that retains crucial file information so that data can be validated and used in court. These tools perform functions in these major categories: Acquisition, Validation and Discrimination, Extraction, Reconstruction, and Reporting. Not all of these functions are needed for E-Discovery. E-Discovery tools are designed to analyzed data that has not been deleted and search for files and other information that could be relevant in a case. 

Digital forensics tools are used to capture hard drive images as part of the duty to preserve. They can also be used to mount forensic images in read-only mode so that other tools can be used to extract or search for relevant data. In addition, they can identify deleted foles, registry entries, and partial files and carve through a hard drive's free space to find file and data fragment. Although digital forensics tools are designed to collect data in a manner that retains crucial file information so that data can be validated and used in court, the process an examiner uses to extract relevant data is equally important. Many digital forensics and E-Discovery tools offer activity logging to capture the examiner's actions when using the software. Activity logging creates a record of the examiner's actions as well as system activities and events. When evidence items are added or searches are created or modified, the activity log records these events and places timestamps in the log file. This log can be used to review search settings and summaries of search result. 

Two E-Discovery and Digital Forensic Software tools are : EnCase, and FTK Imager. 
  1. *Encase* - EnCase is a computer forensics tool designed by Guidance Software. It is an industry accepted tool used in numerous investigations by law enforcement and private companies. EnCase is used to acquire, analyze, and report on evidence. The program creates an .E01 image file when acquiring hard drives, which is the standard format for EnCase. When acquiring a hard drive, the investigator can either do a physical or logical acquisition. Physical acquisition is the process of imaging the entire drive and seeing all data on it, including items that have been deleted and hidden files. Logical acquisition is when the image is viewed in the same format as the computer file system. EnCase also verifies the drive image with the original drive using MD5 and SHA1 hash values and checksums.
  2. *FTK Imager* - FTK Imager is a commercial forensic imaging software distributed by AccessData. The program creates images from hard drives and other types of storage devices. FTK can create images in four different file formats: .E01, SMART, AFF, and Raw. These images can be one file or be split into segments that can be constructed later on. When the file is split into segments, the files can be moved and stored in several locations.

## Comparison of the Pros in Encase and FTK Imager 
|EnCase      | FTK Imager |     
|--------------|-----------------|
|Pros          |        Pros     |        
|It is a very user friendly tool. Encase wins the race here as well by supporting the analyst with user friendly interface.|It has a simple user interface and advanced searching capabilities.|
|With the paid version of Encase which supports all utilities, it also has a free version which can be used for evidence acquisition which is very easy to use. This tool is known as the Encase Imager.|FTK supports EFS decryption.|
|In terms of processing and analysis features, this tool also has good reporting functionalities built into it.|It produces a case log file.|
|With the increase in cyber threats, encryption plays a significant role in securing data in any type or kind of system. Encase has built in support for almost all types of encryption including Bitlocker, MacAfee, Symantec, Sophos etc.|It has significant bookmarking and salient reporting features.|
|Good keyword searching capabilities and scripting features are available.|FTK Imager is free.|


## Comparison of the Cons in EnCase and FTK Imager
|EnCase      | FTK Imager |     
|--------------|-----------------|
|Cons          |        Cons     | 
|This is a very expensive tool.|FTK does not support scripting features.|
|Encase processing can take a lot of time in case of very large compound files and mail boxes.|It does not have multi-tasking capabilities.|
|The latest versions of Encase sometimes are not compatible with other forensic based tools.|There is no progress bar to estimate the time remaining.|
|There is much usage of Encase for mobile forensics.|FTK does not have a timeline view.|


## Tutorial
Here you will the link, that gives an overview of how install EnCase and FTK Imager.
  * EnCase - https://www.youtube.com/watch?v=2FGgUw8Iyw4
  * FTK Imager - https://www.youtube.com/watch?v=zuvjw6m8vo8


Here you will see a link, that gives you an overview of how to use Encase and FTK Imager.
  * EnCase - https://www.youtube.com/watch?v=usTsrBT5w_w
  * FTK Imager - https://www.youtube.com/watch?v=Ca-9LWmau5Q
  
