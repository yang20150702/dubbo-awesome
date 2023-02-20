# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.118 ops/ms
# Warmup Iteration   2: 6.709 ops/ms
# Warmup Iteration   3: 7.915 ops/ms
Iteration   1: 8.229 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.286 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.278 ±(99.9%) 0.820 ops/ms [Average]
  (min, avg, max) = (8.229, 8.278, 8.318), stdev = 0.045
  CI (99.9%): [7.458, 9.098] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.784 ops/ms
# Warmup Iteration   2: 8.559 ops/ms
# Warmup Iteration   3: 8.950 ops/ms
Iteration   1: 8.763 ops/ms
Iteration   2: 8.700 ops/ms
Iteration   3: 8.919 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.794 ±(99.9%) 2.063 ops/ms [Average]
  (min, avg, max) = (8.700, 8.794, 8.919), stdev = 0.113
  CI (99.9%): [6.731, 10.857] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.167 ops/ms
# Warmup Iteration   2: 8.054 ops/ms
# Warmup Iteration   3: 8.220 ops/ms
Iteration   1: 8.326 ops/ms
Iteration   2: 8.511 ops/ms
Iteration   3: 8.227 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.355 ±(99.9%) 2.628 ops/ms [Average]
  (min, avg, max) = (8.227, 8.355, 8.511), stdev = 0.144
  CI (99.9%): [5.726, 10.983] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.055 ops/ms
# Warmup Iteration   2: 6.209 ops/ms
# Warmup Iteration   3: 6.426 ops/ms
Iteration   1: 6.727 ops/ms
Iteration   2: 6.765 ops/ms
Iteration   3: 6.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.675 ±(99.9%) 2.273 ops/ms [Average]
  (min, avg, max) = (6.533, 6.675, 6.765), stdev = 0.125
  CI (99.9%): [4.402, 8.948] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.287 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.792 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.812 ±(99.9%) 0.003 ms/op
Iteration   1: 3.863 ±(99.9%) 0.004 ms/op
Iteration   2: 3.890 ±(99.9%) 0.003 ms/op
Iteration   3: 3.926 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.893 ±(99.9%) 0.575 ms/op [Average]
  (min, avg, max) = (3.863, 3.893, 3.926), stdev = 0.032
  CI (99.9%): [3.317, 4.468] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.916 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.859 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.643 ±(99.9%) 0.003 ms/op
Iteration   1: 3.680 ±(99.9%) 0.004 ms/op
Iteration   2: 3.694 ±(99.9%) 0.002 ms/op
Iteration   3: 3.654 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.676 ±(99.9%) 0.368 ms/op [Average]
  (min, avg, max) = (3.654, 3.676, 3.694), stdev = 0.020
  CI (99.9%): [3.308, 4.044] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.538 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.949 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.713 ±(99.9%) 0.003 ms/op
Iteration   1: 3.810 ±(99.9%) 0.003 ms/op
Iteration   2: 3.840 ±(99.9%) 0.009 ms/op
Iteration   3: 3.683 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.778 ±(99.9%) 1.521 ms/op [Average]
  (min, avg, max) = (3.683, 3.778, 3.840), stdev = 0.083
  CI (99.9%): [2.256, 5.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 5.727 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 5.257 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.097 ±(99.9%) 0.023 ms/op
Iteration   1: 4.726 ±(99.9%) 0.036 ms/op
Iteration   2: 4.631 ±(99.9%) 0.006 ms/op
Iteration   3: 4.815 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.724 ±(99.9%) 1.676 ms/op [Average]
  (min, avg, max) = (4.631, 4.724, 4.815), stdev = 0.092
  CI (99.9%): [3.048, 6.400] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.366 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 4.000 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.965 ±(99.9%) 0.011 ms/op
Iteration   1: 3.836 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.694 ms/op
                 createUser·p0.95:   5.022 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  10.817 ms/op
                 createUser·p0.9999: 15.084 ms/op
                 createUser·p1.00:   15.352 ms/op

Iteration   2: 3.844 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.971 ms/op
                 createUser·p0.50:   3.777 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   4.997 ms/op
                 createUser·p0.99:   5.988 ms/op
                 createUser·p0.999:  9.093 ms/op
                 createUser·p0.9999: 18.045 ms/op
                 createUser·p1.00:   18.481 ms/op

Iteration   3: 3.758 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.900 ms/op
                 createUser·p0.50:   3.711 ms/op
                 createUser·p0.90:   4.612 ms/op
                 createUser·p0.95:   4.915 ms/op
                 createUser·p0.99:   6.144 ms/op
                 createUser·p0.999:  12.050 ms/op
                 createUser·p0.9999: 21.381 ms/op
                 createUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 251731
  mean =      3.812 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6998 
    [ 2.500,  5.000) = 232629 
    [ 5.000,  7.500) = 11007 
    [ 7.500, 10.000) = 830 
    [10.000, 12.500) = 98 
    [12.500, 15.000) = 61 
    [15.000, 17.500) = 35 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.833 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.661 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      6.111 ms/op
     p(99.9000) =     10.195 ms/op
     p(99.9900) =     20.452 ms/op
     p(99.9990) =     21.938 ms/op
     p(99.9999) =     22.020 ms/op
    p(100.0000) =     22.020 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.044 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.872 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.755 ±(99.9%) 0.009 ms/op
Iteration   1: 3.719 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.665 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   4.612 ms/op
                 existUser·p0.95:   4.891 ms/op
                 existUser·p0.99:   5.923 ms/op
                 existUser·p0.999:  13.108 ms/op
                 existUser·p0.9999: 14.805 ms/op
                 existUser·p1.00:   15.204 ms/op

Iteration   2: 3.679 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.349 ms/op
                 existUser·p0.50:   3.650 ms/op
                 existUser·p0.90:   4.506 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  8.765 ms/op
                 existUser·p0.9999: 16.643 ms/op
                 existUser·p1.00:   18.973 ms/op

Iteration   3: 3.617 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.861 ms/op
                 existUser·p0.50:   3.613 ms/op
                 existUser·p0.90:   4.514 ms/op
                 existUser·p0.95:   4.792 ms/op
                 existUser·p0.99:   5.644 ms/op
                 existUser·p0.999:  9.134 ms/op
                 existUser·p0.9999: 18.153 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 261479
  mean =      3.671 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 331 
    [ 1.250,  2.500) = 14348 
    [ 2.500,  3.750) = 132186 
    [ 3.750,  5.000) = 106872 
    [ 5.000,  6.250) = 6247 
    [ 6.250,  7.500) = 718 
    [ 7.500,  8.750) = 365 
    [ 8.750, 10.000) = 203 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 53 
    [13.750, 15.000) = 76 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.349 ms/op
     p(50.0000) =      3.650 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      5.677 ms/op
     p(99.9000) =      9.462 ms/op
     p(99.9900) =     17.882 ms/op
     p(99.9990) =     18.814 ms/op
     p(99.9999) =     18.973 ms/op
    p(100.0000) =     18.973 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.445 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.910 ±(99.9%) 0.010 ms/op
Iteration   1: 3.835 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.628 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   5.947 ms/op
                 getUser·p0.999:  11.610 ms/op
                 getUser·p0.9999: 23.352 ms/op
                 getUser·p1.00:   23.527 ms/op

Iteration   2: 3.796 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.124 ms/op
                 getUser·p0.50:   3.731 ms/op
                 getUser·p0.90:   4.604 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   5.833 ms/op
                 getUser·p0.999:  7.885 ms/op
                 getUser·p0.9999: 25.414 ms/op
                 getUser·p1.00:   25.821 ms/op

Iteration   3: 3.818 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.036 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.686 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   5.882 ms/op
                 getUser·p0.999:  12.538 ms/op
                 getUser·p0.9999: 18.088 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 251403
  mean =      3.816 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5821 
    [ 2.500,  5.000) = 234898 
    [ 5.000,  7.500) = 10020 
    [ 7.500, 10.000) = 398 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 41 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 21 

  Percentiles, ms/op:
      p(0.0000) =      1.036 ms/op
     p(50.0000) =      3.752 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      4.932 ms/op
     p(99.0000) =      5.890 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     24.965 ms/op
     p(99.9990) =     25.672 ms/op
     p(99.9999) =     25.821 ms/op
    p(100.0000) =     25.821 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 7.092 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.130 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 5.055 ±(99.9%) 0.017 ms/op
Iteration   1: 4.896 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.694 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.201 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   8.995 ms/op
                 listUser·p0.999:  16.941 ms/op
                 listUser·p0.9999: 19.807 ms/op
                 listUser·p1.00:   20.316 ms/op

Iteration   2: 4.847 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.005 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.250 ms/op
                 listUser·p0.95:   6.889 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  16.973 ms/op
                 listUser·p0.9999: 18.920 ms/op
                 listUser·p1.00:   19.562 ms/op

Iteration   3: 4.709 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.307 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   5.874 ms/op
                 listUser·p0.95:   6.693 ms/op
                 listUser·p0.99:   8.356 ms/op
                 listUser·p0.999:  23.002 ms/op
                 listUser·p0.9999: 33.698 ms/op
                 listUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199480
  mean =      4.816 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 560 
    [ 2.500,  5.000) = 139596 
    [ 5.000,  7.500) = 53849 
    [ 7.500, 10.000) = 4650 
    [10.000, 12.500) = 437 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 27 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      6.128 ms/op
     p(95.0000) =      6.849 ms/op
     p(99.0000) =      8.602 ms/op
     p(99.9000) =     17.319 ms/op
     p(99.9900) =     31.725 ms/op
     p(99.9990) =     35.324 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.278 ± 0.820  ops/ms
ClientGrpc.existUser                       thrpt       3   8.794 ± 2.063  ops/ms
ClientGrpc.getUser                         thrpt       3   8.355 ± 2.628  ops/ms
ClientGrpc.listUser                        thrpt       3   6.675 ± 2.273  ops/ms
ClientGrpc.createUser                       avgt       3   3.893 ± 0.575   ms/op
ClientGrpc.existUser                        avgt       3   3.676 ± 0.368   ms/op
ClientGrpc.getUser                          avgt       3   3.778 ± 1.521   ms/op
ClientGrpc.listUser                         avgt       3   4.724 ± 1.676   ms/op
ClientGrpc.createUser                     sample  251731   3.812 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.833           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.752           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.661           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.981           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.111           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.195           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.452           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.020           ms/op
ClientGrpc.existUser                      sample  261479   3.671 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.349           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.650           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.809           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.677           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.462           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.882           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.973           ms/op
ClientGrpc.getUser                        sample  251403   3.816 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.036           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.932           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.890           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.699           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.965           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          25.821           ms/op
ClientGrpc.listUser                       sample  199480   4.816 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.005           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.128           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.849           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.602           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.319           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          31.725           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.324           ms/op
