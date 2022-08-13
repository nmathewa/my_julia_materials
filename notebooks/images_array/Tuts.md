```julia
using Pkg
Pkg.add("Images")
using Images

img_url = "https://camo.githubusercontent.com/bc12bdbdd55ba75fd009d59f23385f4fa0a19a1abf7205b0067ff59947b75547/68747470733a2f2f63646e2d73686f702e61646166727569742e636f6d2f31323030783930302f323838352d30362e6a7067"

file_img = download(img_url)

img_ = load(file_img)

```