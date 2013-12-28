# T2G Resource Hub

This is a repository of various learning resources that the teen development community may find useful, in technology competencies such as **UI/UX Design**, **Front-End Development**, and **Back-End Development**.

## Contribute

### Add to the list(s)

Adding to this list is currently done via pull request. To do so, simply modify the ```_harp/_data.json``` file's relevant section in a new branch. For example, to add a paid resource, simply add the following to the relevant section:

```json
"nameOfResource": {
  "name": "New Resource - What Resource Is",
  "url": "http://path/to/new/resource",
  "paid": true
}
```

### Contribute to development

First, here's some technical specifications:

* All code is compiled from [Jade](http://jade-lang.com) and [LESS](http://lesscss.org) to HTML and CSS

* Asset Pipeline is [HarpJS](http://harpjs.com) (v0.10.0), compiles all the Jade/LESS files in the ```_harp/``` folder to static HTML/CSS in the primary folder

* Hosted on Github Pages

To run the server on your local machine, you first need NodeJS and NPM. Then, install harp like:

```bash
$ sudo npm install -g harp
```

Then, go into the directory of the project and type:

```bash
$ harp server _harp
```

Your server should then be running at ```localhost:9000```. From there, make all modifications to the Jade and LESS files in the ```_harp``` directory.

