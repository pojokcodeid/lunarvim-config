# lunarvim-config
## Lakukan instalasi sesuai panduan, cek link berikut : <br>
https://www.lunarvim.org/docs/installation
## Copy Config 
```
mv ~/.config/lvim ~/.config/lvim_bak
git clone https://github.com/pojokcodeid/lunarvim-config ~/.config/lvim
```

## Lakukan perubahan dashboard 
```
lvim.builtin.alpha.dashboard.section.header.val = {
	[[             _       _                    _      ]],
	[[            (_)     | |                  | |     ]],
	[[ _ __   ___  _  ___ | | __   ___ ___   __| | ___ ]],
	[[| '_ \ / _ \| |/ _ \| |/ /  / __/ _ \ / _` |/ _ \]],
	[[| |_) | (_) | | (_) |   <  | (_| (_) | (_| |  __/]],
	[[| .__/ \___/| |\___/|_|\_\  \___\___/ \__,_|\___|]],
	[[| |        _/ |                                  ]],
	[[|_|       |__/                                   ]],
}
local function footer()
	return "Pojok Code"
end
lvim.builtin.alpha.dashboard.section.footer.val = footer()
```
ambil ASCII Dashoard dari : <br>
https://patorjk.com/software/taag/