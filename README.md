```

	██████╗  ██████╗ ████████╗██████╗ ██████╗  ██████╗
	██╔══██╗██╔═══██╗╚══██╔══╝██╔══██╗██╔══██╗██╔═══██╗
	██║  ██║██║   ██║   ██║   ██████╔╝██████╔╝██║   ██║
	██║  ██║██║   ██║   ██║   ██╔══██╗██╔══██╗██║   ██║
	██████╔╝╚██████╔╝   ██║   ██████╔╝██║  ██║╚██████╔╝
	╚═════╝  ╚═════╝    ╚═╝   ╚═════╝ ╚═╝  ╚═╝ ╚═════╝

```

[PUBUIM](https://pubu.im) **DOTBRO** music on demand [extension](https://pubu.im/integrations).

It allows members in your team demand musics by a command. <img src="./screenshot.png" width="450" >


## Usage

- Prepare a server with a stand alone IP address and media output
- Build dotbro service _(or setup on [Raspberry Pi](https://www.raspberrypi.org/) like this article [《如何用树莓派共享办公室的音箱》](http://www.jianshu.com/p/fe8d06a8f751))_
	- Install [nvm](https://github.com/creationix/nvm)
	- Clone the code and enter directory
	- Run `nvm i && npm i`
	- Start service with [forever](https://github.com/foreverjs/forever) or [pm2](https://github.com/Unitech/pm2)
- Setup dotbro extension ([how](http://docs.pubu.im/command.html))
- Run command on [PUBUIM](https://pubu.im) _(example: `/play http://music.163.com/#/m/song?id=37202356`)_

## Resource and license

Media resource provide by [NeteaseMusic](https://music.163.com).

## TODO

- More media resources supporting...
