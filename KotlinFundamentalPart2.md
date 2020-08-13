# Kotlin-Fundamental Part 2

# Numbers
    fun main () {
    val panjang = "20"
    val lebar = 12.6
    val tinggi = 10
    val volume: Double

    println("Volume dari balok yang mempunyai  " + panjang + lebar
    + tinggi))
    }
    fun hitungVolume (p : Double, l : Double, t : Double) : Float
    {
        val v = p * l * t
    println("ini adalah" + v)
    }

# Nullable Types

    fun main (){
    ver word : String? = "SMK Telkom"
    var WordLength = word?.lenght
    print ("Jumlah kata dari string SMK Telkom sabanyak $WordLenght")
    }
    
# Save Calls and Elvis Operator

    fun main (){
    ver word : String? = "SMK Telkom"
    var WordLength = word?.lenght
    print ("Jumlah kata dari string SMK Telkom sabanyak $WordLenght")
    }
    
# String Template

    fun main() {
    val name = "Kotlin"
    val age = 4
    val version = "1,3,70"
    print("""
            Nama saya &name
            Saya berusia &age tahun
            Saya ini sudah mencapai versi &version
    """.trimIndent())
    }
