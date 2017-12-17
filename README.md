using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Windows.Forms;

namespace WindowsFormsApplication3
{
    public partial class Form3 : Form
    {
        public Form3()
        {
            InitializeComponent();
        }

        private void button1_Click(object sender, EventArgs e)
        {
            int a = 0;
                a=Convert.ToInt32(textBox2.Text);
                for (int i = 0; i <= a; i++)
                { 
                if(i %= 3)
                    {
                    textBox1.Text=textBox1+"\r\n"+Convert.ToString(i);
                    }
                }
        }
    }
}


