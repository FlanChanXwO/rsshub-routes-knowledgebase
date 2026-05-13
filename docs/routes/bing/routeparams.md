# Bing - 每日壁纸

## Coverage
`index-only`

## Route
- Namespace: `bing`
- Namespace Name: `Bing`
- Route Path: `/:routeParams?`
- Route Name: `每日壁纸`
- Example: `/bing/type=UHD&story=1&lang=zh-CN`
- URL: `www.bing.com/`
- Language: `zh-CN`
- Categories: `None`
- Maintainers: `FHYunCai, LLLLLFish`
- Source Location: `daily-wallpaper.ts`
- Source Module: `() => import('@/routes/bing/daily-wallpaper.ts')`

## Description
| 参数    | 含义                 | 接受的值                                                      | 默认值       | 备注                                                     |
|-------|--------------------|-----------------------------------------------------------|-----------|--------------------------------------------------------|
| type  | 输出壁纸的像素类型          | UHD/1920x1080/1920x1200/768x1366/1080x1920/1080x1920_logo | 1920x1080 | 1920x1200与1080x1920_logo带有水印,输入的值不在接受范围内都会输出成1920x1080 |
| story | 是否输出壁纸的故事          | 1/0                                                       | 0         | 输入的值不为1都不会输出故事                                         |
| lang  | 输出壁纸图文的地区(中文或者是英文) | zh/en                                               | zh     | zh/en输出的壁纸图文不一定是一样的;如果en不生效,试着部署到其他地方               |

## Parameters
- `routeParams`: 额外参数type,story和lang:请参阅以下说明和表格


## Features
_None_

## Radar
### Rule 1
- `source`:
  - `www.bing.com/`
- `target`: ``
### Rule 2
- `source`:
  - `cn.bing.com/`
- `target`: ``

## Raw JSON
```json
{
  "description": "| 参数    | 含义                 | 接受的值                                                      | 默认值       | 备注                                                     |\n|-------|--------------------|-----------------------------------------------------------|-----------|--------------------------------------------------------|\n| type  | 输出壁纸的像素类型          | UHD/1920x1080/1920x1200/768x1366/1080x1920/1080x1920_logo | 1920x1080 | 1920x1200与1080x1920_logo带有水印,输入的值不在接受范围内都会输出成1920x1080 |\n| story | 是否输出壁纸的故事          | 1/0                                                       | 0         | 输入的值不为1都不会输出故事                                         |\n| lang  | 输出壁纸图文的地区(中文或者是英文) | zh/en                                               | zh     | zh/en输出的壁纸图文不一定是一样的;如果en不生效,试着部署到其他地方               |\n",
  "example": "/bing/type=UHD&story=1&lang=zh-CN",
  "location": "daily-wallpaper.ts",
  "maintainers": [
    "FHYunCai",
    "LLLLLFish"
  ],
  "module": "() => import('@/routes/bing/daily-wallpaper.ts')",
  "name": "每日壁纸",
  "parameters": {
    "routeParams": "额外参数type,story和lang:请参阅以下说明和表格"
  },
  "path": "/:routeParams?",
  "radar": [
    {
      "source": [
        "www.bing.com/"
      ],
      "target": ""
    },
    {
      "source": [
        "cn.bing.com/"
      ],
      "target": ""
    }
  ],
  "url": "www.bing.com/"
}
```
