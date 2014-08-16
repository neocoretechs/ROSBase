ROSBase
=======

Provides org.ros.internal.message.GenerateInterfaces to create Java bindings from ROS message files

Set ROS_PACKAGE_PATH shell variable to <path_to_message_files>

java -cp <all_the_jars> org.ros.internal.message.GenerateInterfaces <output_dir>

To generate the Java bindings for the message files. 
build.xml ant task will JAR up the files to RosBase.jar
