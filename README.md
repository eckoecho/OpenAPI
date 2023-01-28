# OpenAI

If you are like me, I like writing prompts to kick off my creativty. This small writing prompt is especially useful when having to write a professional description about your previous roles. I've created a script to ease any writer's block you may have!  
Some websites out there that will analyze your resume and pick out keywords or are a paid service. But, I find they don't have the robust feedback and damn near conciseness that OpenAI displays. Yet, sometimes it will output complete nonsense (you'll see!). However, it does provide experience in directing ChatGPT and utilizing its API and regressive learning models for your LinkedIn description benefit.
This project incorporates [OpenAIs](https://beta.openai.com/docs/guides/completion) 
`text-davinci-edit-001` [model](summarization for a specific audience and creative content generation) to:
* write a LinkedIn profile description based off of a small portion of text about yourself
* ingest text from a PDF resume and adapt it to meet the job description of your choice

## Prerequisites:
* For ease of working between programming and writing I use [Jupyter Notebooks](https://jupyter.org/) thru the writing prompts.
* For security purposes, knowledge of [how to store your OpenAI keys](https://stackoverflow.com/questions/37890898/how-to-set-env-variable-in-jupyter-notebook) is assumed.  

## Files:
`LinkedInProfile.ipynb` --> Writing prompts and methodology I used to write my bio. <br/>
`StartResume.ipynb` --> Takes your resume in PDF format, creates a string and inserts it into a prompt, resulting in an output to help you re-create your resume based on a specified role. <br/>
