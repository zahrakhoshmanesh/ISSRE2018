# ISSRE2018 Memphis, TN October, 15-18
## My plan
 - Monday(Morning Session)
   - Doctoral Symposium  
 - Monday (Afternoon Session)
 - Tuesday (Morning Session)
 - Tuesday(Afternoon Session)
 - Wednesday (Morning Session)
 - Wednesday (Afternoon Session)
 - Thursday (Morning Session)
 - Thursday (Afternoon Session)


#### Keynote: Having the cake and eating it (Mladen Vouk)
talking about pursuing work in university vs. industry
- professional begging
- staying in academy
  - start-up
  - administration

#### Safety Analysis for highly automated driving. Tobias Schmid

- highly automated Systems
- failsafe
   - fail-silent
   - fail operational, fail-degraded
     - redundant architecture
- common cause failure
- qualitative approach lack applicability and standards
  - creating checklist structure
  - deriving a methodical process based on the literature
  - validation
     - case study
     - validation by field datasets
     - identification of common cause failure
- quantification
  - old : related to 1980 nuclear planet
  - analyzing failure of failure datasets
  - common cause are established in other industries
  - corellating vehicle charactericts and common cause environment
  - identifying of necessary independence

  summary

  - fail-operational affords Systems
  -


#### Testing Extract-Transform-Load Process in Data Warehouse Systems. Hajar Homayouni

- testing
  - data quality testing
   - expert based
  - balancing tests
   -
- how to detect constraint violation that are missed by domain experts?
- how to automated
- data quality test approaches
- proposed balancing test approach
- evaluating :
  - previously detected by existing tool vs. newly detected
  - metrics for balancing :
    - number of faults
    - total timely
- detect undetected faults,
- newly detected faults are faulty by unsupervised approaches
   - use unsupervised clustering to group newly detected fault based on their similarity
   - ask domain experts to validate each group of faults
- want to genralize and reduced domain base approach : unsupervised

#### Software Reliability Assessment: Modeling and Algorithms. Vidhyas Nagaraju

- SRGM: software reliability growth models
-  framework for heteregenous single changepoint software reliability growth models
- changepoint and coevoriate
- before and after change point :
  - applied ECM algorithm to identify paramete estimate
  - online changepoint analysis is demonestrated
  - heteregenous models characterize 6 out of 10 failures
  - SERAT( software reliability tool in R)





#### Enhancing Security and Reliability for Smart-* Systems' Architectures. Florian Hofer









Classroom 227 , Monday, October 15th, 2:00PM - 5:30PM (3:30PM-4:00 Coffee break),
**Tutorial 2: Anomaly Detection in Networks.**

Speaker: **Veena Mendiratta (Nokia Bell Labs, USA)**

 **Abstract**

The application of analytics methods to data collected from communication networks provides valuable information about the network state, and for detecting and predicting anomalous behavior in the network. Large volumes of operation data, including textual and log files, are collected from communication networks; and the inherent value of this data is recognized by academics, practitioners as well as network operators, who need easy to use and robust methods to detect and analyze anomalies based on the network data. The anomalies are indicators of vulnerabilities in the network. From an operations perspective, it is important to detect the anomalies and correct the problem (based on knowing the root cause) in a timely manner. The goal of this tutorial is to deliver a balanced mix of theory and hands-on practice. The first part of the tutorial will focus on introducing analytics methods for network anomaly detection. Next, a real-world case study is presented applying non-parametric machine learning techniques and PCA based methods to detect anomalies in wireless networks. Once an anomaly is detected, message patterns are analyzed for root cause analysis by comparing the message patterns of the anomaly data to those of the normal data to determine where the problems are occurring. Neural network based Kohonen Self Organizing Maps (SOMs) and visual analytics are also used for exploring the anomalous behavior. Data from a 4G network will be used for the analyses. The case study is significant, as communications traffic on wireless networks generates large
volumes of log metadata with hundreds of fields including error codes on a continuous basis across the various servers involved in a communication session. The last third of the tutorial will provide a hands-on session where attendees will be guided in the analysis of real log data using the techniques described above, in particular, the use of Kohonen SOMs. The hands-on session will focus on exploratory data analysis and modeling approaches using the provided (real) datasets. The hands-on session will be conducted using: the R software environment, the rstudio user interface for R, and various R packages.
