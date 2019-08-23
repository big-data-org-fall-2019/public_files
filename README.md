# Week 1 Presentations
- [Syllabus](https://github.com/big-data-org-fall-2019/public_files/blob/master/new_syllabus_2019_v1.pdf)
- [Course Intro](https://github.com/big-data-org-fall-2019/public_files/blob/master/IntroToCourse_fall2019.pdf)
- [Using OSC](https://github.com/big-data-org-fall-2019/public_files/blob/master/UsingOSC_part1_fall2019.pdf)


# Reading Assignments

This is a list of reading assignments associated with each set of topics we will cover throughout the course.  

I plan to give short "reading quizzes" which will be extremely trivial if you have at least read through (or watched, if it is a video) the material once before coming to class.

## Week 2: Data preparation and plotting.   Read/view before coming to class Tuesday August 27.
- Watch this: Using pandas: a short [pandas intro video.](https://www.youtube.com/watch?v=dcqPhpY7tWk)
The video uses the "titanic" dataset, which can be found on the scratch area on OSC at this location:
    
         /fs/scratch/PAS1585/titanic/titanic3.xls

**If** you want to go along with the video, you will need to replace the line:
    
    titanic_df = pd.read_excel('titanic3.xls','titanic3',index_col=None,na_values=['NA'])    
    
with:
    
    titanic_df = pd.read_excel('/fs/scratch/PAS1585/titanic/titanic3.xls','titanic3',index_col=None,na_values=['NA'])
    

- Read though this: A simple tutorial using pandas: https://bitbucket.org/hrojas/learn-pandas/src/master/
This has alot of lessons on pandas which will be very helpful.   At the very least, go through lesson 1.   If you have time, you can copy snippets of the code from this lesson into you own jupyter notebook to practice.

 
