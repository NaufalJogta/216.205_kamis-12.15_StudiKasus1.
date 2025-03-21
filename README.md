#include <iostream>
#include <string>

using namespace std;
struct DataPenduduk {
    string nik,nama,tempatTglLahir,jenisKelamin,golonganDarah,alamat,rt,Rw,kelurahanDesa,kecamatan,agama,statusPerkawinan,pekerjaan,kewarganegaraan,berlakuHingga,provinsi,kabupatenKecamatan;
    
};

int main() {
   
    DataPenduduk data;
    data.nik;
    data.nama;
    data.tempatTglLahir;
    data.jenisKelamin;
    data.golonganDarah;
    data.alamat;
    data.rt;
	data.Rw;
    data.kelurahanDesa;
    data.kecamatan;
    data.agama;
    data.statusPerkawinan;
    data.pekerjaan;
    data.kewarganegaraan;
    data.berlakuHingga = " SEUMUR HIDUP ";
    data.provinsi;
    data.kabupatenKecamatan;

    
    cout << "Masukkan NIK Anda: "; cin>>data.nik;
    cout << "Provinsi: "; cin>>data.provinsi;
    cout << "Kabupaten/Kecamatan: ";cin>>data.kabupatenKecamatan;
    cout << "Masukkan Nama Anda: "; cin>>data.nama;
    cout << "Masukkan Tempat/Tgl Lahir Anda: "; cin>>data.tempatTglLahir;
    cout << "Jenis Kelamin: "; cin>>data.jenisKelamin;
    cout << "Masukkan Golongan Darah Anda: "; cin>>data.golonganDarah;
    cout << "Masukkan Alamat Anda: "; cin>>data.alamat;
    cout << "Masukkan RT Anda: "; cin>>data.rt;
    cout << "Masukkan RW Anda: "; cin>>data.Rw;
    cout << "Masukkan Kelurahan/Desa Anda: "; cin>>data.kelurahanDesa;
    cout << "Masukkan Kecamatan Anda: "; cin>>data.kecamatan;
    cout << "Agama: "; cin>>data.agama;
    cout << "Status Perkawinan: "; cin>>data.statusPerkawinan;
    cout << "Masukkan Pekerjaan Anda: "; cin>>data.pekerjaan;
    cout << "Kewarganegaraan: "; cin>>data.kewarganegaraan;
    cout << endl;
    
	cout << "					PROVINSI " << data.provinsi << endl;
	cout << "					  KABUPATEN " << data.kabupatenKecamatan << endl;
    cout << "NIK" << "              : " << data.nik << endl;
    cout << "Nama" << "             : " << data.nama << endl;
    cout << "Tempat/Tgl Lahir" << " : " << data.tempatTglLahir << endl;
    cout << "Jenis Kelamin" << "    : " << data.jenisKelamin << endl;
    cout << "Alamat" << "           : " << data.alamat;
    cout << "			Gol. Darah  : " << data.golonganDarah << endl;
    cout << "	  RT/RW" << "            : " << data.rt<<"/"<<data.Rw<< endl;
    cout << "	  Kel/Desa" << "         : " << data.kelurahanDesa << endl;
    cout << "	  Kecamatan" << "        : " << data.kecamatan << endl;
    cout << "Agama" << "            : " << data.agama << endl;
    cout << "Status Perkawinan" << ": " << data.statusPerkawinan << endl;
    cout << "Pekerjaan" << "        : " << data.pekerjaan << endl;
    cout << "Kewarganegaraan" << "  : " << data.kewarganegaraan << endl;
    cout << "Berlaku Hingga" << "   : " << data.berlakuHingga << endl;
    cout << endl;

    return 0;
}
