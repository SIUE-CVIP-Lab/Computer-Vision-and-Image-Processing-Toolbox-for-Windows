# Computer-Vision-and-Image-Processing-Toolbox-for-Windows

![Screenshot (439)](https://user-images.githubusercontent.com/60895200/98564945-9cf74900-2272-11eb-834e-d7daa1b6ae41.png)

# About CVIPtools

* CVIPtools is designed for the exploration of computer imaging by allowing the user to interactively experiment with computer imaging techniques, functions and algorithms. It is designed to be used for education, as well as for research and development. It is an on-going project developed at Southern Illinois University at Edwardsville in the Computer Vision and Image Processing Laboratory under the direction of Scott E Umbaugh, PhD.
          
# The current version is 5.8I
 

# Function Categories:
- Arithmetic and Logic
- Band
- Color
- Conversion of Image Files
- Edge/Line Detection
- Geometry
- Histogram
- Mapping
- Morphological
- Noise
- Objective Fidelity
- Pattern Classification: Algorithm Testing
- Pattern Classification: Classification Algorithm
- Pattern Classification: Distance Similarity Metrics
- Pattern Classification: Feature Extraction
- Pattern Classification: Normalization Methods
- Segmentation
- Spatial Filters: Adaptive Filters
- Spatial Filters: Mean Filters
- Spatial Filters: Miscellaneous
- Spatial Filters: Order Filters
- Compression
- Transform
- Transform Filters: Standard
- Transform Filters: Restoration


<h1>Copyright &#169; 2019-2020 <a href="http://www.siue.edu/~sumbaug/">Scott E Umbaugh </a></h1>

# The Program

* CVIPtools currently has two primary platforms: Windows and MATLAB. For the Windows platform, CVIPtools is a collection of computer imaging tools providing services to the users at four layers: the C function layer, the COM interface layer, the CVIPImage layer and the Graphical User Interface (GUI). The C function layer consists of all image and data processing procedures and functions. The Common Object Module (COM) interface layer implements the COM interface for the higher level CVIPtools functions. The CVIPImage layer encapsulates the COM interface functions and provides an Object Oriented Programming (OOP) approach. The GUI implements the image queue and manages user input and resultant output. The MATLAB based version of CVIPtools consists of a Toolbox with M-files corresponding to the C functions, and a GUI for ease of use. The CVIPtools GUI and the MATLAB CVIP Toolbox GUI allow even the casual computer users to experiment with many of the sophisticated tools available to computer imaging specialists without the need for any knowledge of computer programming.

# Development History

* Scott Umbaugh designed the first version of CVIPtools in 1992, which was implemented by Greg Hance. Much development was done with this text menu-driven version by Scott Umbaugh, Greg Hance, Arve Kjoelen, Mark Zuke and Kun Luo from 1993-95. Scott Umbaugh and Mark Zuke designed the graphical user interface in 1995-96, which was implemented by Mark Zuke and Yansheng Wei. The CVIPtcl and CVIPwish shells were initially designed by Scott Umbaugh and Kun Luo and implemented by Kun Luo and Zhen Li in 1995-96. Arve Kjoelen provided system support from 1994-97, as well as doing development work with CVIPtools. Yansheng Wei developed extensive enhancements to CVIPtools during 1996-97, including a complete re-organization and cleanup of the code. Wen Zheng and Sreenivas Makam assisted Scott Umbaugh and Yansheng Wei with the final production of the first publicly released version in 1997, version 3.6. Sreenivas Makam, Wen Zheng and Aek Chomaitong worked on the development of version 3.7 in 1997-1998. Aek Chomaitong, Satish Sammanna, and Lu Guo completed the first release of this as version 3.7c in Fall 1998. Ragavendar Swamisai and Yue Cheng worked on the development of version 3.9 in 1999-2002 and also completed the release of this version in Fall 2002. The CVIPtools TclViewer for CVIPtools3.9 version was developed by Satish Sammanna, Ragavendar Swamisai and Craig Pohl. XVQ compression function was created by Lu Guo and Yue (Iris) Cheng. Transform compression function was created by Zhijian Lin.
 
* The new CVIPtools for Windows was first designed by Scott Umbaugh, Yue (Iris) Cheng, and Dejun Zhang in Fall 2001. The CVIPtools COM interface was first implemented in Visual C++ by Zhang in Spring 2002, with the Main GUI window and image queue written in Visual Basic. Zhang was joined by Xiaohe Chen in Summer 2002 and together they created the first almost complete version Fall 2003. Huashi Ding joined the development team and started with implementing the Utility GUI. Zhang worked on the Analysis and Restoration, while Chen worked on Compression and Enhancement. Husain Kagalwalla joined our team Spring 2004 and worked on the new Help for Windows. The new CVIPlab was developed by Zhang, while Cheng and Ding completed the debugging of the first release version of CVIPtools4.3 Summer 2004.

* The port of CVIPtools to C# began in 2007 by Patrick Solt and Evan Bian. This version of CVIPtools, version 5.3, includes many new CVIP functions, an up-to-date user interface, and two algorithm development programs, CVIP-FEPC and CVIP-ATAT. These programs facilitate algorithm development and batch processing, thereby enabling the CVIPtools users to have a more complete development environment. CVIP-FEPC was created and developed by Patrick Solt. CVIP-ATAT was initially developed by Sid Smith, Jeremy Wood, Geer Shaung, and Evan Bian. Pelin Guvenc and Peng Liu completed CVIP-ATAT for version 5.3. The overall development of CVIPtools5.3 was performed primarily by Patrick Solt and Jhansi Akkineni. Additional development with this version was handled by Hari Krishna Akkineni, Mounika Mamidi, Pelin Guvenc and Serkan Kefel. CVIPtools5.3 was completed in 2010. Hari Siva Kumar Reddy Bhogala worked on the development of CVIPtools version 5.5 and the improvement of CVIP-ATAT in 2013-2014. Additional work was performed for the improvement and enhancement of CVIP-FEPC by Kumari Heema Poudel for version 5.5. CVIPtools version 5.5 was completed in June 2014. Sai Chaitanya Gorantla worked on the additional development of CVIPtools version 5.5 and it was completed in June 2015. Sai Chaitanya Gorantla completed version 5.6 in May 2016 which contains the Laws texture features in the Analysis->Feature tab. The newest version of CVIPtools 5.7 was completed by Gita Pant in 2018 which contains the enhancement of CVIPtools and development of CVIP-FEPC.

* The CVIP Toolbox for MATLAB was initially developed by the porting of CVIPtools C functions to mex (MATLAB executable) files by Krishna Regmi in 2013-2014. The mex file development for the project was continued by Deependra Mishra in 2015. After encountering numerous complications with various versions of compilers and operating systems, we decided to continue development of the CVIP Toolbox using m-files in 2016. Mehrdad Alvandipour and Norsang Lama teamed up with Deependra to complete the first m-file version in 2017. Lakshmi Gorantla and Akhila Karlapalem continued development and testing, and created the first released version of the CVIP Toolbox for MATLAB in March 2018, version 2.5. In 2017 Julian Rene Cuellar Buritica started work on a GUI-based version of CVIPtools in MATLAB using the CVIP Toolbox, including testing and debugging of the CVIP Toolbox functions. In 2019, Sujata Bista and Murat Aslan performed an additional testing of the CVIP Toolbox functions by using a student version of MATLAB to verify the non-MATLAB toolbox dependence of the CVIP Toolbox. In summer 2019, Julian completed version 3.3 of the GUI-based MATLAB CVIPtools that was included in the MATLAB CVIP Toolbox 3.3 release. Naveena Gorre, Andrew Widmar and Joseph Olden contributed to the creation and testing of the MATLAB CVIP Toolbox version 3.3. Julian was the primary developer, with Naveena on the Enhancement window, Andrew on the Restoration->Frequency Filters, and Joseph on the Enhancement->Geometric Transforms.

# Primary CVIPtools Windows Version Developers
* Scott Umbaugh, Dejun Zhang, Xiaohe Chen, Huashi Ding, Yue (Iris) Cheng, Husain Kagalwalla,, Patrick Solt, Wenjun(Evan) Bian, Hu Wang, Jhansi Lakshmi Akkineni, Hari Krishna Akkineni, Mounika Mamidi, Pelin Guvenc, Serkan Kefel, Jakia Afruz, Peng Liu, Hari Siva Kumar Reddy Bhogala, Kumari Heema Poudel, Sai Chaitanya Gorantla,Rohini Dahal, Gita Pant, Naveena Gorre, Charles Goldstein, Charles Stacey

# Primary CVIPtools UNIX Verison Developers
* Scott Umbaugh, Gregory Hance, Arve Kjoelen, Kun Luo, Mark Zuke, Yansheng Wei

# Additional CVIPtools UNIX Version Developers
 * Zhen Li, Wenxing Li, Wen Zheng, Sreenivas Makam, Aek Chomaitong, Satish Sammanna, Lu Guo, Ragavendar Swamisai, Yue (Iris) Cheng 

# CVIPtools Contributors
* Mark Heffron, Asif Haswarey, Melvin Johnson, Ambal Ramachandran, Sridhar Ramalingam, Ramesh Reddy, John Creighton, Brad Walker, Jianxin Tan, Hong Niu, Dave Lyons, Simon Low, Marc Thompson, Muthu Sankarasubbu, Srinivas Madiraju, Frank Smith, Steve Costello, Joseph Tsai, Ivan Lambov, Brad Noble, Robert McClean, Lance Kendrick, Chandra Swaminathan, Praveen Chandr, Kui Cai, Craig Pohl, Zhijian Lin, Subhashini Srinivasan, Sushuma Gouravaram, Geer Shuang, Amit Kharbanda, Ray Walter, Justin Trumpet, Nabin Mishra, Nilesh Shakya, Ravneet Kaur, Jiyuan Fu, Samrat Subedi, Krishna Regmi.

# CVIPtools Web Site Developers 
* Scott Umbaugh, Yansheng Wei, Xiaohe Chen, Geer Shuang, Wenjun (Evan) Bian, Peng Liu, Jiyuan Fu, Rohini Dahal, Gita Pant, Julian Rene Cuellar Buritica, Charles Stacey

# MATLAB CVIP Toolbox Developers 
* Scott Umbaugh, Krishna Regmi, Deependra Mishra, Norsang Lama, Mehrdad Alvandipour, Lakshmi Gorantla, Akhila Karlapalem, Julian Rene Cuellar Buritica, Sujata Bista, Murat Aslan, Naveena Gorre, Joseph Olden, Andrew Widmar,Hridoy Biswas
