# eldred-release

艾尔德雷德冒险界面的发布文件。卡里的加载器按提交号取这里的文件，逐个核对 sha256 后才执行。

- `heavy/shell.js`：冒险界面外壳（已压缩）
- `data/pool-crisis.json`、`data/pool-peace.json`：两个世界的卡池
- `yard/pages.json`：东门外的小院（小院和三个小游戏的整页文档）
- `manifest.json`：版本、素材版本、每个文件的 sha256 和字节

只往前提交，不改历史。图片和字体不在这里，在图床上，按素材版本分文件夹存放。
