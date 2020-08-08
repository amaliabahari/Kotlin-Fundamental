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
Output :
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
Output :
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
Output : 
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
Output : 
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
Output : 
SMK Telkom Purwokerto berdiri pada tanggal 30 Januari 1993
Thats true bro
Process finished with exit code 0

# Function
fun main() {

    val user = setUser("Amel", 16)
    println(user)
}
fun setUser(name: String, age: Int) = "My name is $name,I like listening to music, and i'm $age years old"

Output : 
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
Output :
Nilai kamu 90 selamat ya!
Process finished with exit code 0

