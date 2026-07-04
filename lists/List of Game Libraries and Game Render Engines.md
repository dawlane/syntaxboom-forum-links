# List of Game Libraries and Game Render Engines

This is is going to be the start of a list of useful links to various game libraries and game render engines. If anyone adds some gems, then they will be added to this post, so people don't have to go through every post.

**NOTE:** Many of these sites linked here, have not been fully checked or validated for what contents they offer, and possibly in the future they may also be broken. Anyone using the links should remain vigilant to protect themselves from malicious software and sites through the use of internet security software and good judgement by not falling prey to sites that require the specific entry of personal information. The accuracy of the descriptions may also not be correct, and should be in many cases considered a work-in-progress.
If they don't appear to be what is advertised, or look suspicious.
Then PM an administrator so they can be removed, or updated with the correct information.  
**So use these links and any associated software from these sites at your own risk!**

### 2D-Only

These engines and frameworks are strictly designed for 2D development. They lack native 3D rendering pipelines, 3D coordinate space math, or 3D physics engines.

- [Adventure Game Studio](#adventure-game-studio)
- [Click Team Fusion](#clickteam-fusion)
- [Construct](#construct)
- [Phaser](#phaser)
- [PyGame](#pygame)
- [Pygame Community Edition](#pygame-community-edition)
- [pyxel](#pyxel)
- [The Python Arcade Library](#python-arcade-library)
- [Usagi Engine](#usagi-engine)

### 3D & Hybrid Game Engines

These entries are either dedicated entirely to 3D graphics or are hybrid tools natively supporting both 2D and 3D scenes.

- [App Game Kit (AGK)](#app-game-kit-agk)
- [C4 Engine](#c4-engine)
- [CryEngine](#cryengine)
- [Cube 2 Engine](#cube-2-engine)
- [Dagor Engine](#dagor-engine)
- [Defold](#defold)
- [g2n Engine](#g2n-engine-g3n)
- [GDevelop](#gdevelop)
- [Godot](#godot)
- [jMonkeyEngine](#jmonkeyengine)
- [O3DE](#o3de)
- [Ren'Py](#renpy)
- [Stride](#stride)
- [Unigine](#unigine)
- [Unity](#unity)
- [Unreal Engine](#unreal-engine)
- [Ursina Engine](#ursina-engine)

### Frameworks & Libraries

- [Babylon.js](#babylonjs)
- [Bevy Engine](#bevy-engine)
- [ClanLib](#clanlib)
- [Cocos2D-x](#cocos2d-x)
- [Hord3d](#horde3d)
- [libgdx](#libgdx)
- [MonoGame](#monogame)
- [Ogre](#ogre)
- [RayLib](#raylib)

### Low-Level Libraries & Window Managers

- [bgfx](#bgfx)
- [GLFW](#glfw)
- [SDL: Simple DirectMedia Layer](#sdl-simple-directmedia-layer)

## 2D-Only

<a name="adventure-game-studio"></a>
<table name="adventure-game-studio" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.adventuregamestudio.co.uk/">Adventure Game Studio</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Adventure_Game_Studio">Adventure Game Studio</a>
            is a specialized 2D game engine designed primarily for creating classic point-and-click adventure games in the style of Sierra and LucasArts titles. It provides room editors, dialog systems, inventory management, scripting support, character animation tools, and GUI creation facilities tailored specifically to adventure game development.
        </td>
        <td valign="top">
            <a href="https://github.com/adventuregamestudio/ags/blob/master/License.txt">Artistic License 2.0</a>
        </td>
        <td valign="top">
            AGS Script, C++
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, and iOS
        </td>
    </tr>
</table>

<br>

<a name="clickteam-fusion"></a>
<table name="clickteam-fusion" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.clickteam.com/clickteam-fusion-2-5">Clickteam Fusion</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Clickteam_Fusion">Clickteam Fusion</a>
            is a visual game development environment focused on rapid 2D game creation without requiring traditional programming. Development is performed through an event-driven editor that allows users to build games using conditions, actions, and object interactions. It is popular among indie developers and educational environments.
        </td>
        <td valign="top">
            <a href="https://www.clickteam.com/">Commercial Proprietary License</a>
        </td>
        <td valign="top">
            Event System, JavaScript (extensions), C++ (extensions)
        </td>
        <td valign="top">
            Windows, Android, iOS, HTML5, macOS, Linux, and Xbox
        </td>
    </tr>
</table>

<br>

<a name="construct"></a>
<table name="construct" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.construct.net/">Construct</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Construct_(game_engine)">Construct</a>
            is a browser-based game engine specializing in 2D game development using a visual event-sheet workflow. It emphasizes rapid prototyping, HTML5 deployment, and ease of use for developers with little or no programming experience while still supporting advanced scripting.
        </td>
        <td valign="top">Commercial Proprietary License</br>
            <a href="https://www.construct.net/en/make-games/buy-construct">See pricing</a>
        </td>
        <td valign="top">
            Event Sheets, JavaScript
        </td>
        <td valign="top">
            HTML5, Windows, Linux, macOS, Android, and iOS
        </td>
    </tr>
</table>

<br>

<a name="phaser"></a>
<table name="phaser" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://phaser.io/">Phaser</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Phaser_(game_framework)">Phaser</a>
            is a popular open-source HTML5 game framework designed for 2D browser and mobile game development. It provides rendering, animation, physics integration, asset management, audio support, and scene management for modern web-based games.
        </td>
        <td valign="top">
            <a href="https://github.com/phaserjs/phaser/blob/master/license.txt">MIT License</a>
        </td>
        <td valign="top">
            JavaScript, TypeScript
        </td>
        <td valign="top">
            HTML5 Browsers, Windows, Linux, macOS, Android, iOS
        </td>
    </tr>
</table>

<br>

<a name="pygame"></a>
<table name="pygame" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.pygame.org/">PyGame</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Pygame">PyGame</a>
            is a widely used Python library built on SDL that provides 2D graphics rendering, sound playback, input handling, sprite management, and multimedia functionality. It is frequently used for education, prototyping, and indie game development.
        </td>
        <td valign="top">
            Main Licence: <a href="https://github.com/pygame/pygame/blob/main/docs/LGPL.txt">LGPL License</a></br><a href="https://github.com/pygame/pygame/tree/main/docs/licenses">Other licences</a>
        </td>
        <td valign="top">
            Python
        </td>
        <td valign="top">
            Windows, Linux, macOS, FreeBSD, Raspberry Pi
        </td>
    </tr>
</table>

<br>

<a name="pygame-community-edition"></a>
<table name="pygame-community-edition" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://pyga.me/">Pygame Community Edition</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://github.com/pygame-community/pygame-ce">Pygame Community Edition</a>
            is a community-driven continuation of the PyGame project that provides modern maintenance, bug fixes, performance improvements, and expanded platform support while retaining compatibility with the original PyGame API.
        </td>
        <td valign="top">
            Main Licence: <a href="https://github.com/pygame-community/pygame-ce/blob/main/docs/LGPL.txt">LGPL License</a></br><a href="https://github.com/pygame-community/pygame-ce/tree/main/docs/licenses">Other licences</a>
        </td>
        <td valign="top">
            Python
        </td>
        <td valign="top">
            Windows, Linux, macOS, FreeBSD, Raspberry Pi
        </td>
    </tr>
</table>

<br>

<a name="pyxel"></a>
<table name="pyxel" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://github.com/kitao/pyxel">pyxel</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            Pyxel is a retro-inspired Python game engine that intentionally restricts color palettes, sprite sizes, and audio capabilities to emulate classic 8-bit and 16-bit game hardware. It is optimized for creating pixel-art games with minimal complexity.
        </td>
        <td valign="top">
            <a href="https://github.com/kitao/pyxel/blob/main/LICENSE">MIT License</a>
        </td>
        <td valign="top">
            Python
        </td>
        <td valign="top">
            Windows, Linux, macOS, Web Browser
        </td>
    </tr>
</table>

<br>

<a name="python-arcade-library"></a>
<table name="python-arcade-library" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://arcade.academy/">The Python Arcade Library</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            The Python Arcade Library
            is a modern Python framework for 2D game development built around OpenGL acceleration. It offers sprite rendering, physics integration, tile map support, particle systems, GUI components, and educational resources intended to simplify game programming.
        </td>
        <td valign="top">
            <a href="https://github.com/pythonarcade/arcade/blob/development/license.rst">MIT License</a>
        </td>
        <td valign="top">
            Python
        </td>
        <td valign="top">
            Windows, Linux, macOS
        </td>
    </tr>
</table>

<br>

<a name="usagi-engine"></a>
<table name="usagi-engine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://usagiengine.com/">Usagi Engine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            Usagi Engine
            is a lightweight Lua-based 2D game engine focused on pixel-art game development and rapid prototyping. It emphasizes simplicity, low overhead, and a streamlined workflow suitable for hobbyists and small independent projects.
        </td>
        <td valign="top">
            Main Licence: <a href="https://codeberg.org/brettchalupa/usagi/src/branch/main/UNLICENSE">UNLICENSE</a></br><a href="https://codeberg.org/brettchalupa/usagi/src/branch/main/THIRD_PARTY_LICENSES.md">Other Licenses</a>
        </td>
        <td valign="top">
            Lua
        </td>
        <td valign="top">
            Windows, Linux, macOS
        </td>
    </tr>
</table>

</br>

## 3D & Hybrid Game Engines

<a name="app-game-kit-agk"></a>
<table name="app-game-kit-agk" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.appgamekit.com/">AppGameKit (AGK)</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/AppGameKit">AppGameKit</a> is a cross-platform game development engine focused on simplicity and rapid development. It provides both a beginner-friendly BASIC-style scripting language and a C++ interface. AGK supports the creation of both 2D and 3D games with integrated graphics, physics, audio, networking, and deployment tools.
        </td>
        <td valign="top">
            <a href="https://www.appgamekit.com/">Commercial Proprietary License</a>
        </td>
        <td valign="top">
            AGK BASIC, and C++
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, and HTML5
        </td>
    </tr>
</table>

<br>

<a name="c4-engine"></a>
<table name="c4-engine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://c4engine.com/">C4 Engine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/C4_Engine">C4 Engine</a> is a mature commercial 3D game engine featuring advanced rendering, physics integration, networking support, scripting systems, terrain tools, animation systems, and world editing capabilities. It was designed to support professional-quality real-time 3D applications and games.
        </td>
        <td valign="top">
            <a href="https://c4engine.com/">Commercial Proprietary License</a>
        </td>
        <td valign="top">
            C++, and Script Extensions
        </td>
        <td valign="top">
            Windows, macOS, and Linux
        </td>
    </tr>
</table>

<br>

<a name="cryengine"></a>
<table name="cryengine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.cryengine.com/">CryEngine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/CryEngine">CryEngine</a> is a high-end AAA game engine known for advanced real-time rendering, large-scale environments, physically based rendering, visual scripting, character animation systems, AI tools, and cinematic-quality graphics. It has powered numerous commercially successful first-person shooters and open-world titles.
        </td>
        <td valign="top">
            <a href="https://www.cryengine.com/support/view/licensing">Commercial Source-Available License</a>
        </td>
        <td valign="top">
            C++, C#, Lua, and Visual Scripting
        </td>
        <td valign="top">
            Windows, Linux, PlayStation, and Xbox
        </td>
    </tr>
</table>

<br>

<a name="cube-2-engine"></a>
<table name="cube-2-engine" style="border: 1px solid">
    <tr>
        <th>
            <a href="http://sauerbraten.org/"><b style="color: red">Cube 2 Engine !CAUTION: Not a https web address</b></br></a><a href="https://sourceforge.net/projects/sauerbraten/"><b>Files host on Sourceforge</b></a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Cube_2:_Sauerbraten">Cube 2 Engine</a> is the engine behind Sauerbraten and was designed primarily for fast-paced first-person shooter development. It emphasizes real-time map editing, lightweight architecture, efficient rendering, multiplayer support, and modding flexibility.
        </td>
        <td valign="top">
            <a href="http://sauerbraten.org/README.html#license">See License for usage</a>
        </td>
        <td valign="top">
            C++, and CubeScript
        </td>
        <td valign="top">
            Windows, Linux, macOS, and BSD
        </td>
    </tr>
</table>

<br>

<a name="dagor-engine"></a>
<table name="dagor-engine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://github.com/GaijinEntertainment/DagorEngine">Dagor Engine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://gaijinentertainment.github.io/DagorEngine/dagor-home/dagor_engine.html">Dagor Engine</a> is the proprietary technology originally developed by Gaijin Entertainment and used in titles such as War Thunder. It features advanced rendering systems, large-scale environments, simulation-oriented architecture, networking systems, and modern graphics APIs.
        </td>
        <td valign="top">
            <a href="https://github.com/GaijinEntertainment/DagorEngine/blob/main/LICENSE">BSD 3-Clause License</a>
        </td>
        <td valign="top">
            C++, and <a href="https://en.wikipedia.org/wiki/Squirrel_(programming_language)">Squirrel</a>
        </td>
        <td valign="top">
            Windows, Linux, macOS, PlayStation, and Xbox
        </td>
    </tr>
</table>

<br>

<a name="defold"></a>
<table name="defold" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://defold.com/">Defold</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Defold">Defold</a> is an open-source game engine primarily known for 2D game development but featuring true 3D scene support, model rendering, lighting, cameras, and physics. It provides an integrated editor, asset pipeline, hot reloading, and efficient deployment workflows.
        </td>
        <td valign="top">
            <a href="https://github.com/defold/defold/blob/dev/LICENSE.txt">Defold License (Open Source)</a>
        </td>
        <td valign="top">
            Lua, C++, and Java (Extensions)
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, HTML5, and Nintendo Switch
        </td>
    </tr>
</table>

<br>

<a name="g2n-engine-g3n"></a>
<table name="g2n-engine-g3n" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://github.com/g3n/engine">g3n Engine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://github.com/g3n/engine/wiki">g3n Engine</a> is a fully featured 3D game engine and graphics framework written entirely in Go. It provides scene graphs, animation systems, lighting, materials, model loading, GUI components, and OpenGL rendering capabilities while remaining native to the Go ecosystem.
        </td>
        <td valign="top">
            <a href="https://github.com/g3n/engine/blob/master/LICENSE">BSD 2-Clause License</a>
        </td>
        <td valign="top">
            Go
        </td>
        <td valign="top">
            Windows, Linux, and macOS
        </td>
    </tr>
</table>

<br>

<a name="gdevelop"></a>
<table name="gdevelop" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://gdevelop.io/">GDevelop</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/GDevelop">GDevelop</a> is an open-source visual game engine that began as a 2D development environment but now includes a real-time 3D engine, model support, lighting systems, physics integration, visual scripting, and cross-platform deployment tools. It is designed to allow non-programmers to create complete games.
        </td>
        <td valign="top">
            <a href="https://github.com/4ian/GDevelop/blob/master/LICENSE.md">MIT License</a>
        </td>
        <td valign="top">
            Event Sheets, JavaScript, and TypeScript
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, and HTML5
        </td>
    </tr>
</table>

<br>

<a name="godot"></a>
<table name="godot" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://godotengine.org/">Godot</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Godot_(game_engine)">Godot</a> is a fully open-source game engine providing dedicated 2D and 3D rendering pipelines, integrated scene editing, animation systems, physics engines, scripting support, networking, XR capabilities, and extensive editor tooling. It is widely used for both indie and professional game development.
        </td>
        <td valign="top">
            <a href="https://github.com/godotengine/godot/blob/master/LICENSE.txt">MIT License</a>
        </td>
        <td valign="top">
            GDScript, C#, C++, VisualScript, and GDExtension Languages
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, HTML5, PlayStation, Xbox, and Nintendo Switch
        </td>
    </tr>
</table>

</br>

<a name="jmonkeyengine"></a>
<table name="jmonkeyengine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://jmonkeyengine.org/">jMonkeyEngine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/JMonkeyEngine">jMonkeyEngine</a> is an open-source Java game engine focused on modern 3D game development. It provides scene graph management, physics integration, animation systems, terrain rendering, networking, shader support, and an SDK built on the NetBeans platform. It is widely used for educational, simulation, and indie game projects.
        </td>
        <td valign="top">
            <a href="https://github.com/jMonkeyEngine/jmonkeyengine/blob/master/LICENSE.md">BSD 3-Clause License</a>
        </td>
        <td valign="top">
            Java, Kotlin, Scala, Groovy, and Other JVM Languages
        </td>
        <td valign="top">
            Windows, Linux, macOS, and Android
        </td>
    </tr>
</table>

<br>

<a name="o3de"></a>
<table name="o3de" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://o3de.org/">O3DE (Open 3D Engine)</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Open_3D_Engine">Open 3D Engine</a> is a large-scale open-source AAA game engine governed by the Linux Foundation. Derived from Amazon Lumberyard, it provides physically based rendering, visual scripting, animation systems, multiplayer networking, terrain generation, robotics integration, simulation support, and modern editor tooling.
        </td>
        <td valign="top">
            <a href="https://github.com/o3de/o3de/blob/development/LICENSE.txt">Apache License 2.0</a>
        </td>
        <td valign="top">
            C++, Python, Lua, and Script Canvas
        </td>
        <td valign="top">
            Windows, Linux, Android, and iOS
        </td>
    </tr>
</table>

<br>

<a name="renpy"></a>
<table name="renpy" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.renpy.org/">Ren'Py</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Ren%27Py">Ren'Py</a> is a visual novel engine primarily designed for 2D storytelling, dialogue systems, branching narratives, and character presentation. Modern versions include support for 3D stages, perspective transforms, matrix manipulation, camera systems, and model rendering, allowing limited but native 3D scene construction.
        </td>
        <td valign="top">
            <a href="https://www.renpy.org/doc/html/license.html">See here</a>
        </td>
        <td valign="top">
            Ren'Py Script, and Python
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, and Web Browsers
        </td>
    </tr>
</table>

<br>

<a name="stride"></a>
<table name="stride" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.stride3d.net/">Stride</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Stride_(game_engine)">Stride</a> is an open-source C# game engine offering physically based rendering, visual scripting, asset management, animation systems, ECS-style architecture, and advanced editor tools. Originally developed as Xenko, it supports both professional game development and visualization projects.
        </td>
        <td valign="top">
            <a href="https://github.com/stride3d/stride/blob/master/LICENSE.md">MIT License</a>
        </td>
        <td valign="top">
            C#, and .NET Languages
        </td>
        <td valign="top">
            Windows, Linux, Android, and iOS
        </td>
    </tr>
</table>

<br>

<a name="unigine"></a>
<table name="unigine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://unigine.com/">Unigine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Unigine">Unigine</a> is a professional-grade real-time 3D engine used extensively for simulation, training, digital twins, scientific visualization, and enterprise applications. It is known for large-world rendering, advanced terrain systems, physically based graphics, VR support, and high-performance simulation capabilities.
        </td>
        <td valign="top">
            Free & Commercial: <a href="https://unigine.com/get-unigine/">See pricing</a>
        </td>
        <td valign="top">
            C++, C#, UnigineScript, and Python
        </td>
        <td valign="top">
            Windows, Linux, PlayStation, Xbox, and VR Platforms
        </td>
    </tr>
</table>

<br>

<a name="unity"></a>
<table name="unity" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://unity.com/">Unity</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Unity_(game_engine)">Unity</a> is one of the most widely used game engines in the industry, supporting both 2D and 3D development. It provides advanced rendering pipelines, animation systems, physics engines, visual effects, networking solutions, editor extensibility, AR/VR support, and extensive asset ecosystem integration.
        </td>
        <td valign="top">
            Free and Commercial: <a href="https://unity.com/products">See pricing</a>
        </td>
        <td valign="top">
            C#, and Visual Scripting
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, WebGL, PlayStation, Xbox, Nintendo Switch, and AR/VR Platforms
        </td>
    </tr>
</table>

<br>

<a name="unreal-engine"></a>
<table name="unreal-engine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.unrealengine.com/">Unreal Engine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Unreal_Engine">Unreal Engine</a> is a leading AAA game engine developed by Epic Games. It provides state-of-the-art rendering technologies such as Nanite and Lumen, Blueprint visual scripting, advanced animation systems, cinematic production tools, multiplayer networking, and extensive support for film, architecture, and simulation workflows.
        </td>
        <td valign="top">
            <a href="https://www.unrealengine.com/en-US/eula/unreal">Commercial Source-Available License</a>
        </td>
        <td valign="top">
            C++, Blueprint Visual Scripting, and Python
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, PlayStation, Xbox, Nintendo Switch, and AR/VR Platforms
        </td>
    </tr>
</table>

<br>

<a name="ursina-engine"></a>
<table name="ursina-engine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.ursinaengine.org/">Ursina Engine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            Ursina Engine is a Python game development framework built on top of Panda3D. It simplifies 3D game creation by providing a higher-level API for scene management, rendering, input handling, UI creation, and rapid prototyping while retaining access to Panda3D's underlying capabilities.
        </td>
        <td valign="top">
            <a href="https://github.com/pokepetter/ursina/blob/master/LICENSE">MIT License</a>
        </td>
        <td valign="top">
            Python
        </td>
        <td valign="top">
            Windows, Linux, and macOS
        </td>
    </tr>
</table>

</br>

## Frameworks & Libraries

<a name="babylonjs"></a>
<table name="babylonjs" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.babylonjs.com/">Babylon.js</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Babylon.js">Babylon.js</a> is a powerful open-source 3D engine and framework for the web. It provides physically based rendering, scene management, animation systems, particle effects, physics integration, WebXR support, audio systems, and advanced tooling for creating browser-based games and interactive visualizations.
        </td>
        <td valign="top">
            <a href="https://github.com/BabylonJS/Babylon.js/blob/master/license.md">Apache License 2.0</a>
        </td>
        <td valign="top">
            JavaScript, and TypeScript
        </td>
        <td valign="top">
            Web Browsers, Windows, Linux, macOS, Android, and iOS (via Browser/WebView)
        </td>
    </tr>
</table>

<br>

<a name="bevy-engine"></a>
<table name="bevy-engine" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://bevyengine.org/">Bevy Engine</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Draft:Bevy_(game_engine)">Bevy Engine</a> is a modern data-driven game framework written in Rust. It uses an Entity Component System (ECS) architecture and supports both 2D and 3D development through modular rendering, asset management, animation, audio, UI, networking integrations, and high-performance parallel processing.
        </td>
        <td valign="top">
            <a href="https://github.com/bevyengine/bevy/blob/main/LICENSE-MIT">MIT License / Apache License 2.0</a>
        </td>
        <td valign="top">
            Rust
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, and WebAssembly
        </td>
    </tr>
</table>

<br>

<a name="clanlib"></a>
<table name="clanlib" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://github.com/sphair/ClanLib">ClanLib</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/ClanLib">ClanLib</a> is a cross-platform C++ game SDK providing graphics, audio, networking, GUI, resource management, and utility modules. Although historically associated with 2D development, it includes OpenGL-based 3D rendering functionality and can be used for both 2D and 3D applications.
        </td>
        <td valign="top">
            <a href="https://github.com/sphair/ClanLib/blob/master/COPYING">Zlib License</a>
        </td>
        <td valign="top">
            C++
        </td>
        <td valign="top">
            Windows, Linux, and macOS
        </td>
    </tr>
</table>

<br>

<a name="cocos2d-x"></a>
<table name="cocos2d-x" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.cocos.com/en/cocos2dx">Cocos2d-x</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Cocos2d">Cocos2d-x</a> is a widely used open-source game framework originally focused on 2D development but later expanded to include 3D scene graphs, cameras, skeletal animation, terrain rendering, lighting systems, and physics support. It is especially popular for mobile game development.
        </td>
        <td valign="top">
            <a href="https://github.com/cocos2d/cocos2d-x/blob/v4/licenses/LICENSE_cocos2d-x.txt">Under it's own licence</a></br><a href="https://github.com/cocos2d/cocos2d-x/tree/v4/licenses">Other licences</a>
        </td>
        <td valign="top">
            C++, Lua, and JavaScript
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, and iOS
        </td>
    </tr>
</table>

<br>

<a name="horde3d"></a>
<table name="horde3d" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.horde3d.org/">Horde3D</a><b sytle="color: red">!CAUTION: Not a https web address</b><a href="https://github.com/horde3d/Horde3D">File host on github</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Horde3D">Horde3D</a> is a lightweight open-source rendering engine designed for real-time 3D graphics applications. It emphasizes high-performance rendering, shader-driven pipelines, scene graph management, skeletal animation, and efficient resource usage while remaining relatively compact and easy to integrate.
        </td>
        <td valign="top">
            <a href="https://www.eclipse.org/legal/epl/epl-v10.html">Eclipse Public License</a>
        </td>
        <td valign="top">
            C++, C#, and Lua (Bindings Available)
        </td>
        <td valign="top">
            Windows, Linux, and macOS
        </td>
    </tr>
</table>

<br>

<a name="libgdx"></a>
<table name="libgdx" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://libgdx.com/">libGDX</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/LibGDX">libGDX</a> is a cross-platform Java game development framework supporting both 2D and 3D applications. It provides graphics APIs, physics integrations, scene management, audio systems, input handling, asset pipelines, UI toolkits, and deployment tools for desktop, mobile, and web targets.
        </td>
        <td valign="top">
            <a href="https://github.com/libgdx/libgdx/blob/master/LICENSE">Apache License 2.0</a>
        </td>
        <td valign="top">
            Java, Kotlin, Scala, and Other JVM Languages
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, and WebAssembly
        </td>
    </tr>
</table>

<br>

<a name="monogame"></a>
<table name="monogame" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://monogame.net/">MonoGame</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/MonoGame">MonoGame</a> is an open-source implementation of Microsoft's XNA Framework. It provides graphics, audio, content management, input handling, shader support, and low-level rendering APIs for both 2D sprite-based games and full 3D applications while remaining close to traditional code-driven development.
        </td>
        <td valign="top">
            <a href="https://github.com/MonoGame/MonoGame/blob/develop/LICENSE.txt">Microsoft Public License (Ms-PL)</a>
        </td>
        <td valign="top">
            C#, F#, VB.NET, and Other .NET Languages
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, PlayStation, Xbox, and Nintendo Switch
        </td>
    </tr>
</table>

<br>

<a name="ogre"></a>
<table name="ogre" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.ogre3d.org/">Ogre</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/OGRE">OGRE (Object-Oriented Graphics Rendering Engine)</a> is a scene-oriented real-time 3D rendering engine focused on graphics rather than full game engine functionality. It provides rendering abstractions, scene management, animation systems, material frameworks, shader support, and plugin-based extensibility.
        </td>
        <td valign="top">
            <a href="https://github.com/OGRECave/ogre/blob/master/LICENSE">MIT License</a>
        </td>
        <td valign="top">
            C++, Python (Bindings Available), and C# (Bindings Available)
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, and iOS
        </td>
    </tr>
</table>

<br>

<a name="raylib"></a>
<table name="raylib" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.raylib.com/">raylib</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Raylib">raylib</a> is a simple and lightweight cross-platform programming library designed to make game programming accessible while still providing support for both 2D and 3D graphics. It includes rendering, audio, input, math utilities, model loading, shaders, and numerous community-maintained language bindings.
        </td>
        <td valign="top">
            <a href="https://github.com/raysan5/raylib/blob/master/LICENSE">Zlib License</a>
        </td>
        <td valign="top">
            C, C++, C#, Rust, Go, D, Zig, Nim, Python, Lua, Java and Many Community Bindings
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, Raspberry Pi, and WebAssembly
        </td>
    </tr>
</table>

</br>

## Low-Level Libraries & Window Managers

<a name="bgfx"></a>
<table name="bgfx" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://github.com/bkaradzic/bgfx">bgfx</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://bkaradzic.github.io/bgfx/overview.html#what-is-it">bgfx</a> is a cross-platform low-level rendering library that abstracts numerous graphics APIs behind a unified interface. Rather than being a game engine, it serves as a rendering backend for custom engines and applications. bgfx supports modern graphics features, shader compilation, multithreaded rendering, resource management, and deployment across desktop, mobile, web, and console platforms.
        </td>
        <td valign="top">
            <a href="https://github.com/bkaradzic/bgfx/blob/master/LICENSE">BSD 2-Clause License</a>
        </td>
        <td valign="top">
            C++, C99 API, Bindings Available for C#, Rust, Go, Zig, D and Others
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, WebAssembly, PlayStation, Xbox, and Nintendo Switch
        </td>
    </tr>
</table>

<br>

<a name="glfw"></a>
<table name="glfw" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.glfw.org/">GLFW</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/GLFW">GLFW</a> is a lightweight cross-platform library for creating windows, OpenGL and Vulkan contexts, handling input devices, managing monitors, and processing events. It is commonly used as the foundation for graphics engines, game engines, rendering frameworks, visualization software, and graphics tutorials.
        </td>
        <td valign="top">
            <a href="https://github.com/glfw/glfw/blob/master/LICENSE.md">Zlib License</a>
        </td>
        <td valign="top">
            C, C++, and Bindings Available for Numerous Languages
        </td>
        <td valign="top">
            Windows, Linux, macOS, Wayland, and X11
        </td>
    </tr>
</table>

<br>

<a name="sdl-simple-directmedia-layer"></a>
<table name="sdl-simple-directmedia-layer" style="border: 1px solid">
    <tr>
        <th>
            <a href="https://www.libsdl.org/">SDL: Simple DirectMedia Layer</a>
        </th>
    </tr>
    <tr>
        <td>Description</td>
        <td>Licensing</td>
        <td>Languages</td>
        <td>Supported Platforms</td>
    </tr>
    <tr>
        <td valign="top">
            <a href="https://en.wikipedia.org/wiki/Simple_DirectMedia_Layer">Simple DirectMedia Layer (SDL)</a> is a widely used cross-platform multimedia and hardware abstraction library. It provides access to graphics hardware, audio devices, keyboards, mice, game controllers, sensors, file systems, networking extensions, and platform services. SDL serves as the foundation for numerous game engines, emulators, media applications, and development frameworks.
        </td>
        <td valign="top">
            <a href="https://github.com/libsdl-org/SDL/blob/main/LICENSE.txt">zlib License (SDL3)</a>
        </td>
        <td valign="top">
            C, C++, Bindings Available for Python, Rust, C#, Go, Java, Lua and Many Others
        </td>
        <td valign="top">
            Windows, Linux, macOS, Android, iOS, FreeBSD, OpenBSD, NetBSD, Haiku, Raspberry Pi, and WebAssembly
        </td>
    </tr>
</table>