## WPS OFFICE Error Fix
<ul>
    <li> sudo snap connections wps-2019-snap </li>
    <li> sudo removable-media wps-2019-snap:removable-media </li>
    <li> sudo snap list </li>
    <li> sudo snap connect wps-2019-snap:removable-media </li>
    <li> sudo snap connections wps-2019-snap </li>
</ul>

### WINE
<ul>
<li> sudo dpkg --add-architecture i386 </li> 
<li> wget -nc https://dl.winehq.org/wine-builds/winehq.key </li> 
<li> wget -nc https://dl.winehq.org/wine-builds/winehq.key | sudo apt-key add winehq.key </li> 
<li> sudo add-apt-repository 'deb https://dl.winehq.org/wine-builds/ubuntu/ focal main' </li> 
<li> sudo apt update </li> 
<li> sudo apt install --install-recommends winehq-stable </li> 
<li> wine --version </li> 
<li> winecfg </li> 
</ul>
