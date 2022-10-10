# _Claire's MVC page_

#### By _**Harold Mesa**_

#### _MVC page for a Hair Salon._

## Technologies Used

* _HTML_
* _CSS_
* _C#_
* _.NET Core_
* _MySQL_
* _Entity_

## Description

_This is an MVC application that stores a list of stylists into a database, and assigns clients to each one._ 

## Setup/Installation Requirements

* _Clone this repository to your desktop_
* _Navigate to HairSalon/ folder_
* _Run $ dotnet restore_
* _Run $ dotnet run_
* _Open http://localhost:5000 on your browser_

* _If you don't have it yet, install MySQL Web Installer. [Here](https://dev.mysql.com/downloads/installer/)'s download link._
* _When installing, select:_ 
* _Use legacy encryption_
* _Set password_
* _Enter the following in your command line:_

### *'export PATH="/usr/local/mysql/bin:$PATH"' >> ~/.bash_profile   

* _Download the MySQL Workbench DMG file [here](https://dev.mysql.com/downloads/file/?id=484391). Open MySQL Workbench._
* _Select >> Local Instance 3306_
* _Import database (harold_mesa.sql) from the project's root folder_
* _Create a file called appsettings.json in HairSalon folder._
* _Copy the following in the file:_
 _{ "ConnectionStrings": { "DefaultConnection": "Server=localhost;Port=3306;database=harold_mesa;uid=root;pwd=[YOUR_PASSWORD_HERE];" } }_

## Known Bugs

* _No known bugs_
* _All tests covered pass_

## License

_[MIT License](https://en.wikipedia.org/wiki/MIT_License)_

_Copyright (c) [2022] [Harold Mesa]_

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

Copyright (c) _30 Sep, 2022_ _Harold Mesa_
