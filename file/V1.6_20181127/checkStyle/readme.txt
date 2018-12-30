CheckStyleRules.xml 是CheckStyle规范，为最高级别版本。
suppression.xml  是指定CheckStyle检查是需要过滤的文件或包，目前只排除了测试文件和目录

注意：如果路径不在一个地方，需要更改CheckStyleRules.xml的最后一个module配置正确的路径：
<module name="SuppressionFilter">
     <property name="file" value="suppression.xml"/>
     <property name="optional" value="false"/>
</module>