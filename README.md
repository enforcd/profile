```cs
using System;
using System.Collections.Generic;
using System.ComponentModel;
using System.Data;
using System.Diagnostics;
using System.Drawing;
using System.Linq;
using System.Text;
using System.Threading.Tasks;
using System.Windows.Forms;

namespace enforcd
{
    public partial class About : Form
    {
        public About()
        {
            InitializeComponent();
        }

  

        private void AboutMe(object sender, EventArgs e)
        {

            MessageBox.Show("Location: United States"  + Enviornment.NewLine + "Languages: Python and C#" + Enviornment.NewLine + "Connetions: Discord");
            MessageBox.Show("My Discord: 768456422366117908");
                
            
        }

    }
}
