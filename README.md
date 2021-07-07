Resume-Interface-app
-----
A React project to create and design your resume and convert to PDF in letter or A4 format.

Is This Project For You
-------
If you are a frontender who is looking to design a resume with the tools that you love and use daily then yes.

``
This is a frontend interface app.created using react.js

Install dependencies and start the project
```
npm i
npm start
```

Download to PDF
--------
Once you finish with filling and designing your resume you can convert it to PDF by running this command
```
npm run convert-pdf -- [options]
```

Options
```
--paperSize     One of 'a4' or 'letter'. alias -p
```

A new pdf file will be generated in the `output/` directory. **NOTE:** Running this command will NOT override the previous generated resumes.

Design Your Resume
-------
You can find all resume templates under [/src/components](/src/components) directory.

All templates will follow this folder structure
```
├── ResumeTemplate         # Template directory
   ├── index.js            # Main component file
   ├── Utils               # Utility components for this template
   ├── Sections            # All supported sections components
   ├── Layout              # Resume layout components e.g. LeftColumn
```

Fill in Your Resume Data
-------
You can find all the data you need to change under [/src/resume](/src/resume) directory.
