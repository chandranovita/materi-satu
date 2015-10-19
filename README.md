# materi-satu
public class materiSatu extends javax.swing.JFrame {
     int nilaiA, nilaiB, nilaiHasil;
     double nilaiA1, nilaiB1, nilaiHasil1;

    /**
     * Creates new form materiSatu
     */
    public materiSatu() {
        initComponents();
    }
    
    void tambah () {
       
        nilaiA = Integer.parseInt(jTextFieldNilai1.getText());
        nilaiB = Integer.parseInt(jTextFieldNilai2.getText());
        nilaiHasil=nilaiA+nilaiB;
        jLabelhasil.setText(""+nilaiHasil); 
    }
    
    void kurang () {
       
        nilaiA = Integer.parseInt(jTextFieldNilai1.getText());
        nilaiB = Integer.parseInt(jTextFieldNilai2.getText());
        nilaiHasil=nilaiA-nilaiB;
        jLabelhasil.setText(""+nilaiHasil); 
    }
    
    void kali () {
       
        nilaiA = Integer.parseInt(jTextFieldNilai1.getText());
        nilaiB = Integer.parseInt(jTextFieldNilai2.getText());
        nilaiHasil=nilaiA*nilaiB;
        jLabelhasil.setText(""+nilaiHasil); 
    }
    
    void bagi () {
       
        nilaiA1 = Double.parseDouble(jTextFieldNilai1.getText());
        nilaiB1 = Double.parseDouble(jTextFieldNilai2.getText());
        nilaiHasil1=nilaiA1/nilaiB1;
        jLabelhasil.setText(""+nilaiHasil1); 
    }
    
    
    materi 2
     private void jButton1ActionPerformed(java.awt.event.ActionEvent evt) {                                         

        Jangan1 j = new Jangan1(); // proses instansiasi
        j.tolongJangan();
        
        
        
        
        dikelasbiasa juga ada
        public class Jangan1 {
    void tolongJangan(){
        JOptionPane.showMessageDialog(null, "Woi, Sudah Dibilang Jangan");   
}

    
    
    
