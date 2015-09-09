allprojects {
    repositories {
        jcenter()
        maven {
            url "https://jitpack.io"
        }
    }
}


and:
dependencies {
    compile fileTree(dir: 'libs', include: ['*.jar'])
    compile 'com.github.cvnhan:calculator:1.2'

}
