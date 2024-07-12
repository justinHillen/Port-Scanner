# Port-Scanner
This project features a Python-based network port scanner designed to assess the status of specific ports on a target host. Using the socket module, the scanner resolves hostnames to IP addresses and establishes TCP connections to the specified ports, determining whether each port is open or closed.

The scanner starts by resolving the target hostname to its IP address, ensuring accurate identification of the target system. It then attempts to retrieve the host name associated with the IP address for detailed scan results. With a default timeout of one second, the scanner tries to connect to each target port, handling potential network delays.

If a connection is successfully established, the port is reported as open, indicating that the target host is accepting connections on that port. If the connection fails, the port is reported as closed, signifying it is either blocked or not in use. This project demonstrates practical skills in network programming and security assessment, offering valuable insights into the accessibility and security of networked systems.
