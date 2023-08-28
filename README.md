# Learning Python – In Jupyter

This is a Python introduction course in [Jupyter notebooks](https://jupyter-notebook.readthedocs.io/en/stable/notebook.html). It consists of 15 chapters of Python basics, covering the basic concepts in the Python programming language. Then, there are six more chapters in the continuation course, covering more advanced concepts and providing challenging exercises. 

The course is for absolute beginners with no prior programming skills. Therefore, the entire course is in Jupyter Notebooks, since this enables you to jump straight to trying out Python code. You won't have to worry about installing everything correctly, using virtual environments, or learning how to use your computer's interactive shell (although, you should learn about these concepts as well, later on). 

To start the course, just follow the guide below. Good luck!

## Get started – A step-by-step guide for the beginner

### 1. Install Anaconda

The best way to quickly get into the course is to download the Anaconda software package ([follow this link](https://www.anaconda.com/products/individual#Downloads)). By using Anaconda, you can be sure you get all Jupyter installations needed to run the course notebook. For Max OS, you get to choose between command line installation and the graphical installer. For beginners, the graphical installer is recommended. 

When you click on your choice of installer, you will get a pop-up window to register to Anaconda Nucleus. This service is not mandatory to run Anaconda, and it is a requirement to proceed with this course. If you don't want this service, just ignore it.

If you run into problems installing Anaconda, [check this guide](https://docs.anaconda.com/anaconda/install/).

When you've downloaded the Anaconda installer, open it and follow the installation instructions as recommended. The installation may take some time. Also, when installing, you will be asked if you want to install VSCode. It is a great code editor, but it is not required in this course. 

**CAUTION:** If you have installed Anaconda already, be sure to check which version of Python that was included. This course won't work with any Python version below 3.6.  

### 2. Open Anaconda Navigator

When you've successfully installed Anaconda, open the Anaconda Navigator program. In Mac, you will find it in your **launchpad** overview:

![image](course_material/readme/launchpad.png)

On Windows 10, you can just search for Anaconda Navigator in the **searchbar**:

![image](course_material/readme/searchbar.png)

### 3. Open Jupyter Notebook

The first time you open Anaconda Navigator, it can take some time to load. When it finally launches, press the Jupyter Notebook `Launch` button:

![image](course_material/readme/navigator.png)

(*Windows users:*, _if a Jupyter Notebook isn't launched_ when you press launch in Ananconda Navigator, there might be a bug. If it doesn't launch properly, you can use the Anaconda prompt to launch Jupyter instead. Search for "anaconda prompt" in the Windows search bar and open it:

![image](course_material/readme/anaconda_prompt.png)

This will open a command line window. Here, simply type `jupyter notebook`, then press enter and it should be launched!)

When you've successfully launched Jupyter, your default browser will open. The first view should be your "home page" in the Jupyter Notebook file tree navigator. It should look similar to this:

![image](course_material/readme/jupyter.png)

### 4. Download the course material

If you are familiar with using github, then just clone this repo. If not, you can download this entire course as a zipfile by pressing these buttons on the top menu of this github page:

![image](course_material/readme/material.png)

When you've downloaded, just unzip the file and put the folder with all material somewhere where you can find it.

### 5. Put the course folder/directory in "Documents"

Ok, it doesn't _have_ to be in the Documents directory. But, it is just that it is a common default name of a folder that can be found in both PC and Mac computers. You just need to place the course material where you can find it, in relation to your home page in the Jupyter Notebook file tree navigator (the view you get when you launch Jupyter Notebook from Anaconda). 

Place your course material here:

![image](course_material/readme/documents.png)

### 6. Open the course in a notebook

Find the course material in the Jupyter Notebook file tree navigator interface. All Jupyter Notebook files have the file extension `.ipynb`. The course notebooks are within two different folders – one folder for Python basics and one for the continuation course. 

You start with the notebooks in the folder "basics_course". This is for the absolute beginner. The first part is named `chapter_1-7.ipynb`, which includes a course introduction. Begin with this file! In the continuation course notebook, we learn about creating and managing files, writing our own text recognition software with regular expressions, and web scraping. There is also a project assignment where you get to extract information from 5,000 pdf files! Lastly, there is a course on the data management library Pandas – highly recommended for those who want to use programming to analyze data.


![image](course_material/readme/course_start.png)

That's it! You can now begin the course. Good luck! Oh, one more thing:

## Beginner? Read this as well

As you can see in the image just above this section, all notebooks included in the course have a small book icon. There is the two parts of the actual course (the files `chapter_1-7.ipynb`and `chapter_8-15.ipynb`), and the notebook with the solutions to the course's exercises – `solutions.ipynb`. 

But I also recommend that you create your own notebook to experiment with. It's easy! You just press the `New` button up on the right and then choose "Python 3" under "Notebook" in the dropdown:

![image](course_material/readme/create_nb.png)

If you want to copy the course notebooks, and experiment directly in them (without risking deleting any course material), this is also possible! Just check the notebook you want to duplicate and press the "Duplicate" button up top:

![image](course_material/readme/duplicate.png)

You can then open the new copy and work in it instead.








