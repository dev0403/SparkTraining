…or create a new repository on the command line

echo "# SparkTraining" >> README.md
git init
git add README.md
git commit -m "first commit"
git remote add origin https://github.com/dev0403/SparkTraining.git
git push -u origin master
…or push an existing repository from the command line

git remote add origin https://github.com/dev0403/SparkTraining.git
git push -u origin master


export JAVA_HOME=/usr/java/jdk1.8.0_151
export PATH=$PATH:$JAVA_HOME/bin
