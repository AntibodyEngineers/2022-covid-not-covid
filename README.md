# COVID not COVID

The overall goal of the work is to demystify machine learning (ML). ML is a large area that encompasses many approaches and details are typically communicated at an expert level and include many terms from statistical methods, neural nets, convolutional neural nets, transformers.  Moreover, the common examples do not apply to the biotech world and often focus on how to sort dogs, cats, and check writing samples. We want to contextualize ML for biotech and get a small amount of practice. Toward the goal of demystifying ML we wanted to have projects where teams learn about input data, ML models, and what they [models] can and cannot do. In this work we trained an ML model that could interpret the protein sequence of an antibody to determine whether that antibody could bind to the receptor binding domain of the SARS-CoV-2 spike protein. To distinguish covid binding antibodies from non binders

## Resources
### Jetstream
We use the NSF supported Jetstream (https://jetstream-cloud.org/) computing resources. From the website: 
> Jetstream2 is a transformative update to the NSF’s science and engineering cloud infrastructure and provides 8 petaFLOPS of supercomputing power to simplify data analysis, boost discovery, and increase availability of AI resources. It is an NSF-funded, user-friendly cloud environment designed to allow “always on” research infrastructure and to give researchers access to interactive computing and data analysis resources on demand, whenever and wherever they want to analyze their data.

For our case we estimated that we would need both GPU- (graphics processing unit) and CPU- (central processing unit) based computers. GPUs are used in high-performance computing applications. In the case of ML, computing models need to be trained on very large datasets and GPUs are often used for purpose. We estimated that we would need a mix of GPUs and CPUs and that the hackathon project would require 120,000 SUs. 120,000 SUs were granted for one year. 

Jetstream provides the overall infrastructure. Users of the platform make computing resources available by creating virtual machines (VMs). A VM is a software instantiation of a computer that includes a number of GPU or CPU processors and a virtual disk of a specified size. Any number of VMs can be made. The size and type of the computer, how long it runs, and computing loads determines the number of SUs that are used. Jetstream provides web-based interfaces that allow one to configure VMs, set them to running, or shelve them. Shelved VMs are a way to preserve work without using SUs. Over the course of the hackathon, and period afterward we used 73,000 of our 120,000 SU allocation.  


https://github.com/alchemab/antiberta
