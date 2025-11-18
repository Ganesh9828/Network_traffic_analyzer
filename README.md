Network Traffic Analyzer

Network Traffic Analyzer is a Python-based tool designed to analyze network traffic captured in PCAP files. It provides insights into communication patterns, protocol usage, bandwidth consumption, and potential security threats such as port scanning activity.

This tool is ideal for network administrators, SOC analysts, and cybersecurity researchers who want a lightweight but effective way to interpret network captures.

 Features

✔ Analyze network traffic from PCAP files
✔ Calculate total bandwidth usage
✔ Display protocol distribution
✔ Identify top communication pairs (source → destination IPs)
✔ Detect potential port scanning behavior
✔ Easy-to-run Python CLI application

 Future Enhancements

Planned updates include:

Graphical plots for IP communication patterns

Latency, packet loss, and throughput analysis

Jitter & network utilization metrics

Error rate computation

Exporting results to CSV/JSON

GUI dashboard (Tkinter/Streamlit)

 Installation
1. Clone the repository
git clone https://github.com/<your-username>/network-traffic-analyzer.git

2. Navigate to the project directory
cd network-traffic-analyzer

3. Install required dependencies
pip install -r requirements.txt

🛠 Usage

To analyze a PCAP file, run:

python Network_traffic_analyzer.py <path_to_pcap_file> <port_scan_threshold>

Example
python Network_traffic_analyzer.py sample.pcap 50


<path_to_pcap_file> → location of your PCAP file

<port_scan_threshold> → number of unique ports accessed before labeling behavior as suspicious

 Contributing

Contributions are welcome! Follow the standard GitHub workflow:

Fork the repository

Create a feature branch

git checkout -b feature/my-feature


Commit changes

git commit -m "Add my feature"


Push the branch

git push origin feature/my-feature


Open a Pull Request

 License

This project is licensed under the MIT License — feel free to use and modify it.
