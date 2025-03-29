 # ArcMap2SLD 插件 v1.4.0 使用说明

 ## 简介

 ArcMap2SLD_Setup_1.4.0 是一款专为ArcGIS用户设计的高效工具，用于将ArcMap中精心配置的地图样式直接导出为SLD（Styled Layer Descriptor）格式。这对于需要在地理信息系统（如GeoServer）中保持地图样式一致性的用户来说，是一个不可或缺的助手。通过这款插件，您可以轻松实现从桌面GIS到Web GIS的风格无缝对接。

 ## 安装与使用步骤

 1. **下载并解压缩**：首先，确保您已从指定源下载了`ArcMap2SLD_Setup_1.4.0`压缩包，并将其解压缩到您的本地硬盘上。

 2. **环境准备**：确保您的计算机已安装了ArcGIS软件。这是插件能够正常工作的前提条件。

 3. **执行批处理文件**：在解压缩后的文件夹中找到 `Adjust_for_ArcGIS-version.bat` 文件并双击运行。这个步骤会为您的ArcGIS环境设置必要的配置。

 4. **中文支持设置**：
     - 若需中文界面或处理中文地名时，打开名为 `LUT_sld_mapping_file.xml` 的文件。
         - 找到 `<LUT>` 标签内的 `<sldConfiguration>` 节点，在其中的 `<xmlEncoding>` 标签内，原先是 `ISO-8859-1`，您需要将其更改为 `GB2312`。这一步是保证中文正确显示的关键。

         ## 导出SLD文件

         完成上述步骤后，您可以在ArcMap中选择想要导出样式的图层，利用新添加的插件功能，按照提示操作即可将地图样式导出为SLD文件。这使得您的地图风格可以方便地应用于基于Web的服务中，促进了数据和视觉效果的一致性。

         ## 注意事项

         - 在进行任何系统级改动前，请备份重要数据。
         - 确保所有的软件版本兼容，避免因软件版本不匹配导致的问题。
         - 如遇到任何技术问题，建议参考官方文档或者相关论坛寻求帮助。

         通过此插件，管理和迁移地图样式变得简单快捷，大大提升了工作效率，是ArcGIS用户优化工作流程的优选工具。祝您使用愉快！

         ---

         请注意，提供的信息和步骤应根据实际文件及软件更新情况进行适当调整。

         ## 下载链接
         [ArcMap2SLD插件v1.4.0使用说明](https://pan.quark.cn/s/7c91c7726f1b) 

         (备用: [备用下载](https://pan.baidu.com/s/1ipu8G9bXs37X05NrekRNQw?pwd=1234))
