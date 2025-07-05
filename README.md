<!-- Hero Section -->
<section id="home" class="gradient-bg pt-20 pb-16">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="grid md:grid-cols-2 gap-12 items-center">
            <div class="text-white">
                <h1 class="text-5xl font-bold mb-6">
                    Sewa Kendaraan <span class="text-yellow-300">Terpercaya</span>
                </h1>
                <p class="text-xl mb-8 text-gray-200">
                    Melayani penyewaan mobil, bus, Hiace, ELF, dan truck untuk dalam kota, luar kota, bahkan luar provinsi dengan harga terjangkau.
                </p>
                <a href="https://wa.me/6289677105865?text=Halo%20RATRANS%2C%20saya%20tertarik%20dengan%20layanan%20sewa%20kendaraan" target="_blank" class="bg-yellow-400 text-gray-800 px-8 py-4 rounded-full font-semibold hover:bg-yellow-300 inline-block">
                    <i class="fab fa-whatsapp mr-2"></i>WhatsApp Sekarang
                </a>
            </div>
            <div class="animate-float">
                <div class="bg-white p-8 rounded-2xl shadow-2xl">
                    <h3 class="text-2xl font-bold text-gray-800 mb-6">Booking Cepat</h3>
                    <form id="quick-booking" class="space-y-4">
                        <select name="vehicle" class="w-full p-3 border rounded-lg">
                            <option>Pilih Kendaraan</option>
                            <option>Mobil</option>
                            <option>Bus</option>
                            <option>Hiace</option>
                            <option>ELF</option>
                            <option>Truck</option>
                        </select>
                        <input type="date" name="date" class="w-full p-3 border rounded-lg">
                        <input type="text" name="destination" placeholder="Tujuan" class="w-full p-3 border rounded-lg">
                        <button type="submit" class="w-full bg-blue-900 text-white py-3 rounded-lg font-semibold">
                            Cari Kendaraan
                        </button>
                    </form>
                </div>
            </div>
        </div>
    </div>
</section>

<!-- Vehicle Types -->
<section id="vehicles" class="py-20">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-bold text-gray-800 mb-4">Pilihan Kendaraan Kami</h2>
        </div>
        
        <div class="grid md:grid-cols-2 lg:grid-cols-5 gap-8">
            <!-- Mobil -->
            <div class="bg-white rounded-2xl shadow-lg p-6 card-hover text-center">
                <div class="bg-blue-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-car text-3xl text-blue-900"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Mobil</h3>
                <p class="text-gray-600 mb-4">Sedan, SUV, MPV</p>
                <div class="text-2xl font-bold text-red-900 mb-4">300K/hari</div>
                <button onclick="bookVehicle('Mobil')" class="w-full bg-blue-900 text-white py-2 rounded-lg">
                    Pilih Mobil
                </button>
            </div>

            <!-- Bus -->
            <div class="bg-white rounded-2xl shadow-lg p-6 card-hover text-center">
                <div class="bg-green-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-bus text-3xl text-green-600"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Bus</h3>
                <p class="text-gray-600 mb-4">Medium & Big Bus</p>
                <div class="text-2xl font-bold text-red-900 mb-4">2.5JT/hari</div>
                <button onclick="bookVehicle('Bus')" class="w-full bg-blue-900 text-white py-2 rounded-lg">
                    Pilih Bus
                </button>
            </div>

            <!-- Hiace -->
            <div class="bg-white rounded-2xl shadow-lg p-6 card-hover text-center">
                <div class="bg-orange-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-shuttle-van text-3xl text-orange-600"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Hiace</h3>
                <p class="text-gray-600 mb-4">Van 10-16 orang</p>
                <div class="text-2xl font-bold text-red-900 mb-4">1JT/hari</div>
                <button onclick="bookVehicle('Hiace')" class="w-full bg-blue-900 text-white py-2 rounded-lg">
                    Pilih Hiace
                </button>
            </div>

            <!-- ELF -->
            <div class="bg-white rounded-2xl shadow-lg p-6 card-hover text-center">
                <div class="bg-teal-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-truck-pickup text-3xl text-teal-600"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">ELF</h3>
                <p class="text-gray-600 mb-4">12-20 orang</p>
                <div class="text-2xl font-bold text-red-900 mb-4">1JT/hari</div>
                <button onclick="bookVehicle('ELF')" class="w-full bg-blue-900 text-white py-2 rounded-lg">
                    Pilih ELF
                </button>
            </div>

            <!-- Truck -->
            <div class="bg-white rounded-2xl shadow-lg p-6 card-hover text-center">
                <div class="bg-red-100 w-20 h-20 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-truck text-3xl text-red-600"></i>
                </div>
                <h3 class="text-xl font-bold mb-2">Truck</h3>
                <p class="text-gray-600 mb-4">Angkutan barang</p>
                <div class="text-2xl font-bold text-red-900 mb-4">600K/hari</div>
                <button onclick="bookVehicle('Truck')" class="w-full bg-blue-900 text-white py-2 rounded-lg">
                    Pilih Truck
                </button>
            </div>
        </div>
    </div>
</section>

<!-- Contact -->
<section id="contact" class="py-20 bg-gray-800 text-white">
    <div class="max-w-7xl mx-auto px-4 sm:px-6 lg:px-8">
        <div class="text-center mb-16">
            <h2 class="text-4xl font-bold mb-4">Hubungi Kami</h2>
            <p class="text-xl text-gray-300">Siap melayani 24/7</p>
        </div>
        
        <div class="grid md:grid-cols-3 gap-8 text-center">
            <div>
                <div class="bg-blue-900 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-phone text-2xl"></i>
                </div>
                <h3 class="text-xl font-semibold mb-2">Telepon</h3>
                <a href="tel:+6289677105865" class="text-gray-300 hover:text-white">0896-7710-5865</a>
            </div>
            
            <div>
                <div class="bg-blue-900 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fab fa-whatsapp text-2xl"></i>
                </div>
                <h3 class="text-xl font-semibold mb-2">WhatsApp</h3>
                <a href="https://wa.me/6289677105865" target="_blank" class="text-yellow-400 hover:text-yellow-300">
                    0896-7710-5865
                </a>
            </div>
            
            <div>
                <div class="bg-red-900 w-16 h-16 rounded-full flex items-center justify-center mx-auto mb-4">
                    <i class="fas fa-map-marker-alt text-2xl"></i>
                </div>
                <h3 class="text-xl font-semibold mb-2">Alamat</h3>
                <p class="text-gray-300">Jl. Nusa Indah 72, Kureksari<br>Waru, Sidoarjo</p>
            </div>
        </div>
    </div>
</section>

<!-- Footer -->
<footer class="bg-gray-900 text-white py-8">
    <div class="max-w-7xl mx-auto px-4 text-center">
        <p>&copy; 2024 RATRANS. Semua hak dilindungi.</p>
    </div>
</footer>

<script>
    // Book vehicle function
    function bookVehicle(vehicleType) {
        const message = `Halo RATRANS, saya tertarik dengan Sewa ${vehicleType}. Mohon info lebih lanjut.`;
        window.open(`https://wa.me/6289677105865?text=${encodeURIComponent(message)}`, '_blank');
    }

    // Quick booking form
    document.getElementById('quick-booking').addEventListener('submit', function(e) {
        e.preventDefault();
        const formData = new FormData(this);
        const message = `Halo RATRANS, saya ingin booking:
Kendaraan: ${formData.get('vehicle')}
Tanggal: ${formData.get('date')}
Tujuan: ${formData.get('destination')};
            window.open(https://wa.me/6289677105865?text=${encodeURIComponent(message)}`, '_blank');
});
    // Smooth scrolling
    document.querySelectorAll('a[href^="#"]').forEach(anchor => {
        anchor.addEventListener('click', function (e) {
            e.preventDefault();
            document.querySelector(this.getAttribute('href')).scrollIntoView({
                behavior: 'smooth'
            });
        });
    });
</script>
# Ratrans
Penyedia layanan transportasi dalam kota atau provinsi dan juga luar kota atau provinsi.  
