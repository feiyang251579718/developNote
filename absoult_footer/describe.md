# 固定底部
页面底部固定在最底下，如果页面的长度超过的了屏幕的高度，则footer在整个页面的下方

### function1
body、html、container包裹元素占满全屏，container包裹元素（包含footer、header）使用padding-bottom $footerHeight,footer使用绝对定位的形式总是在底部

### function2
body、html、container包裹元素占满全屏，container包裹内容（不包含footer）使用margin-bottom -$footerHeight的形式进行判定

### function3
body、html、container包裹元素占满全屏，container包裹内容（不包含footer），使用container包含一个高度与footer相同的空元素顶开

### function4
使用js动态计算container的高度