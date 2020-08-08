# Kotlin-Fundamental
# Hello Kotlin
fun main (){
    val name ="Amalia Bahari"
    val hobby ="Listening to music"

    print("Hello my name is")
    println(name)
    print("My hobby is")
    println(hobby)
}
Output : "C:\Program Files\Java\jdk-13.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=54996:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Projek Kotlin\Kotlin Fundament\build\classes\kotlin\main;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.3.72\916d54b9eb6442b615e6f1488978f551c0674720\kotlin-stdlib-jdk8-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.3.72\3adfc2f4ea4243e01204be8081fe63bde6b12815\kotlin-stdlib-jdk7-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.3.72\8032138f12c0180bc4e51fe139d4c52b46db6109\kotlin-stdlib-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.3.72\6ca8bee3d88957eaaaef077c41c908c9940492d8\kotlin-stdlib-common-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar" Hello_KotlinKt
Hello my name isAmalia Bahari
My hobby isListening to music

Process finished with exit code 0

# DataTypes
fun main (){
    val firstWord = "SMK "
    val middleWord = "Telkom "
    val lastWord = "Purwokerto "
    println(firstWord + middleWord + lastWord)

    val hurufAwal = "Luas "
    val hurufTengah = "Persegi "
    val hurufAkhir = "Panjang "
    print(hurufAwal + hurufTengah + hurufAkhir)

    val panjang: Int = 43
    val lebar= 2
    println(panjang * lebar)
}
Output : "C:\Program Files\Java\jdk-13.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=55004:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Projek Kotlin\Kotlin Fundament\build\classes\kotlin\main;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.3.72\916d54b9eb6442b615e6f1488978f551c0674720\kotlin-stdlib-jdk8-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.3.72\3adfc2f4ea4243e01204be8081fe63bde6b12815\kotlin-stdlib-jdk7-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.3.72\8032138f12c0180bc4e51fe139d4c52b46db6109\kotlin-stdlib-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.3.72\6ca8bee3d88957eaaaef077c41c908c9940492d8\kotlin-stdlib-common-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar" DataTypesKt
SMK Telkom Purwokerto 
Luas Persegi Panjang 86

Process finished with exit code 0

# Characters
fun main (){
    var vocal = 'Z'

    print("Huruf Z")
    println()
    print("Huruf Y")
    println()
    print("Huruf X")
    println()
    print("Huruf S")
    println()
    print("Huruf R")
    println()
    print("Huruf S")
    println()
    print("Huruf X")
    println()
    print("Huruf Y")
    println()
    print("Huruf Z")
    println()

}
Output : "C:\Program Files\Java\jdk-13.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=55024:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Projek Kotlin\Kotlin Fundament\build\classes\kotlin\main;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.3.72\916d54b9eb6442b615e6f1488978f551c0674720\kotlin-stdlib-jdk8-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.3.72\3adfc2f4ea4243e01204be8081fe63bde6b12815\kotlin-stdlib-jdk7-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.3.72\8032138f12c0180bc4e51fe139d4c52b46db6109\kotlin-stdlib-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.3.72\6ca8bee3d88957eaaaef077c41c908c9940492d8\kotlin-stdlib-common-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar" CharactersKt
Huruf Z
Huruf Y
Huruf X
Huruf S
Huruf R
Huruf S
Huruf X
Huruf Y
Huruf Z

Process finished with exit code 0

# Strings
fun main () {
    val kotlin = """
        Kotlin is Modern
        Kotlin is Concise
        Kotlin is Pragmatic
        Kotlin is Safe
    """.trimIndent()

    print(kotlin)
}
Output : "C:\Program Files\Java\jdk-13.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=55032:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Projek Kotlin\Kotlin Fundament\build\classes\kotlin\main;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.3.72\916d54b9eb6442b615e6f1488978f551c0674720\kotlin-stdlib-jdk8-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.3.72\3adfc2f4ea4243e01204be8081fe63bde6b12815\kotlin-stdlib-jdk7-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.3.72\8032138f12c0180bc4e51fe139d4c52b46db6109\kotlin-stdlib-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.3.72\6ca8bee3d88957eaaaef077c41c908c9940492d8\kotlin-stdlib-common-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar" StringsKt
Kotlin is Modern
Kotlin is Concise
Kotlin is Pragmatic
Kotlin is Safe
Process finished with exit code 0

# Array
fun main (){
    val mixArray = arrayOf(30, " Januari ", 1993, "SMK Telkom Purwokerto", true)

    print(mixArray[3])
    print(" berdiri pada tanggal ")
    print(mixArray[0])
    print(mixArray[1])
    println(mixArray[2])
    print("Thats ")
    print(mixArray[4])
    print(" bro")
}
Output : "C:\Program Files\Java\jdk-13.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=55043:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Projek Kotlin\Kotlin Fundament\build\classes\kotlin\main;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.3.72\916d54b9eb6442b615e6f1488978f551c0674720\kotlin-stdlib-jdk8-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.3.72\3adfc2f4ea4243e01204be8081fe63bde6b12815\kotlin-stdlib-jdk7-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.3.72\8032138f12c0180bc4e51fe139d4c52b46db6109\kotlin-stdlib-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.3.72\6ca8bee3d88957eaaaef077c41c908c9940492d8\kotlin-stdlib-common-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar" ArrayKt
SMK Telkom Purwokerto berdiri pada tanggal 30 Januari 1993
Thats true bro
Process finished with exit code 0

# Function
fun main() {
    val user = setUser("Amel", 16)
    println(user)
}

fun setUser(name: String, age: Int) = "My name is $name,I like listening to music, and i'm $age years old"
Output : "C:\Program Files\Java\jdk-13.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=55060:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Projek Kotlin\Kotlin Fundament\build\classes\kotlin\main;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.3.72\916d54b9eb6442b615e6f1488978f551c0674720\kotlin-stdlib-jdk8-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.3.72\3adfc2f4ea4243e01204be8081fe63bde6b12815\kotlin-stdlib-jdk7-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.3.72\8032138f12c0180bc4e51fe139d4c52b46db6109\kotlin-stdlib-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.3.72\6ca8bee3d88957eaaaef077c41c908c9940492d8\kotlin-stdlib-common-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar" FunctionKt
My name is Amel,I like listening to music, and i'm 16 years old

Process finished with exit code 0

# If Expressions
fun main(){
    val nilai = 90
    val kkm = 75
    if (nilai >= kkm) {
        println("Nilai kamu " + nilai + " selamat ya!")
    } else{
        println("Nilai kamu " + nilai + " silahkan ikut remidi!")
    }
}
Output : "C:\Program Files\Java\jdk-13.0.2\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\lib\idea_rt.jar=55068:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2020.1.2\bin" -Dfile.encoding=UTF-8 -classpath "C:\Projek Kotlin\Kotlin Fundament\build\classes\kotlin\main;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk8\1.3.72\916d54b9eb6442b615e6f1488978f551c0674720\kotlin-stdlib-jdk8-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-jdk7\1.3.72\3adfc2f4ea4243e01204be8081fe63bde6b12815\kotlin-stdlib-jdk7-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib\1.3.72\8032138f12c0180bc4e51fe139d4c52b46db6109\kotlin-stdlib-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains.kotlin\kotlin-stdlib-common\1.3.72\6ca8bee3d88957eaaaef077c41c908c9940492d8\kotlin-stdlib-common-1.3.72.jar;C:\Users\LENOVO\.gradle\caches\modules-2\files-2.1\org.jetbrains\annotations\13.0\919f0dfe192fb4e063e7dacadee7f8bb9a2672a9\annotations-13.0.jar" If_ExpressionsKt
Nilai kamu 90 selamat ya!

Process finished with exit code 0

