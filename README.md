# Foundation Emails
Responsive HTML emails using the Foundation Zurb email stack.

Gulp-powered build with Handlebars, Inky, Sass, BrowserSync 

**Dependencies**
* [Node.js](http://nodejs.org)
* [Git](http://git-scm.com/downloads)
* [Gulp](http://gulpjs.com/)

Install npm
```
npm install 
```
Foundation install:
```
npm install --global foundation-cli
```
New project
```
foundation new --framework emails
```
Project Folder
```
cd appName
```
Directory
```
http://localhost:8080
```
Run build
```
npm run build
```
Update
```
npm update -g foundation-cli
```

Inky
```
<container>
  <row>
    <columns>Put content in me!</columns>
  </row>
</container>
```

Output
```
<table align="center" class="container">
  <tbody>
    <tr>
      <td>
        <table class="row">
          <tbody>
            <tr>
              <th class="small-12 large-12 columns first last">
                <table>
                  <tr>
                    <th>Put content in me!</th>
                    <th class="expander"></th>
                  </tr>
                </table>
              </th>
            </tr>
          </tbody>
        </table>
      </td>
    </tr>
  </tbody>
</table>
```