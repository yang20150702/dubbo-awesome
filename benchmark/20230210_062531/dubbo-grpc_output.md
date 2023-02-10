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
# Warmup Iteration   1: 5.152 ops/ms
# Warmup Iteration   2: 9.381 ops/ms
# Warmup Iteration   3: 10.419 ops/ms
Iteration   1: 10.220 ops/ms
Iteration   2: 10.461 ops/ms
Iteration   3: 10.146 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.276 ±(99.9%) 3.011 ops/ms [Average]
  (min, avg, max) = (10.146, 10.276, 10.461), stdev = 0.165
  CI (99.9%): [7.264, 13.287] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:55
# Fork: 1 of 1
# Warmup Iteration   1: 8.129 ops/ms
# Warmup Iteration   2: 10.834 ops/ms
# Warmup Iteration   3: 10.963 ops/ms
Iteration   1: 10.887 ops/ms
Iteration   2: 10.656 ops/ms
Iteration   3: 10.700 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.748 ±(99.9%) 2.239 ops/ms [Average]
  (min, avg, max) = (10.656, 10.748, 10.887), stdev = 0.123
  CI (99.9%): [8.509, 12.986] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.777 ops/ms
# Warmup Iteration   2: 10.050 ops/ms
# Warmup Iteration   3: 10.168 ops/ms
Iteration   1: 10.581 ops/ms
Iteration   2: 10.315 ops/ms
Iteration   3: 10.261 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.386 ±(99.9%) 3.129 ops/ms [Average]
  (min, avg, max) = (10.261, 10.386, 10.581), stdev = 0.172
  CI (99.9%): [7.257, 13.515] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.668 ops/ms
# Warmup Iteration   2: 7.721 ops/ms
# Warmup Iteration   3: 8.271 ops/ms
Iteration   1: 7.955 ops/ms
Iteration   2: 8.048 ops/ms
Iteration   3: 7.777 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.927 ±(99.9%) 2.511 ops/ms [Average]
  (min, avg, max) = (7.777, 7.927, 8.048), stdev = 0.138
  CI (99.9%): [5.416, 10.437] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.964 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.194 ±(99.9%) 0.002 ms/op
Iteration   1: 3.154 ±(99.9%) 0.007 ms/op
Iteration   2: 3.129 ±(99.9%) 0.002 ms/op
Iteration   3: 3.178 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.154 ±(99.9%) 0.446 ms/op [Average]
  (min, avg, max) = (3.129, 3.154, 3.178), stdev = 0.024
  CI (99.9%): [2.707, 3.600] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.492 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.014 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.956 ±(99.9%) 0.004 ms/op
Iteration   1: 2.941 ±(99.9%) 0.002 ms/op
Iteration   2: 2.953 ±(99.9%) 0.002 ms/op
Iteration   3: 2.960 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.951 ±(99.9%) 0.178 ms/op [Average]
  (min, avg, max) = (2.941, 2.951, 2.960), stdev = 0.010
  CI (99.9%): [2.773, 3.130] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.735 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.075 ±(99.9%) 0.003 ms/op
Iteration   1: 3.123 ±(99.9%) 0.001 ms/op
Iteration   2: 3.042 ±(99.9%) 0.003 ms/op
Iteration   3: 3.053 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.073 ±(99.9%) 0.803 ms/op [Average]
  (min, avg, max) = (3.042, 3.073, 3.123), stdev = 0.044
  CI (99.9%): [2.270, 3.876] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.411 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.187 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.085 ±(99.9%) 0.045 ms/op
Iteration   1: 3.956 ±(99.9%) 0.009 ms/op
Iteration   2: 4.112 ±(99.9%) 0.009 ms/op
Iteration   3: 4.117 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.062 ±(99.9%) 1.667 ms/op [Average]
  (min, avg, max) = (3.956, 4.062, 4.117), stdev = 0.091
  CI (99.9%): [2.395, 5.729] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.836 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.202 ±(99.9%) 0.009 ms/op
Iteration   1: 3.181 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.404 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.891 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  11.132 ms/op
                 createUser·p0.9999: 17.595 ms/op
                 createUser·p1.00:   17.990 ms/op

Iteration   2: 3.178 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.834 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.119 ms/op
                 createUser·p0.999:  12.829 ms/op
                 createUser·p0.9999: 18.151 ms/op
                 createUser·p1.00:   19.759 ms/op

Iteration   3: 3.013 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.529 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.469 ms/op
                 createUser·p0.95:   3.674 ms/op
                 createUser·p0.99:   4.506 ms/op
                 createUser·p0.999:  8.894 ms/op
                 createUser·p0.9999: 20.858 ms/op
                 createUser·p1.00:   20.972 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 307325
  mean =      3.122 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29425 
    [ 2.500,  5.000) = 273759 
    [ 5.000,  7.500) = 2990 
    [ 7.500, 10.000) = 741 
    [10.000, 12.500) = 124 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 127 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.404 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      4.043 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     11.633 ms/op
     p(99.9900) =     18.776 ms/op
     p(99.9990) =     20.972 ms/op
     p(99.9999) =     20.972 ms/op
    p(100.0000) =     20.972 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.669 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.955 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.925 ±(99.9%) 0.007 ms/op
Iteration   1: 3.013 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.691 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.569 ms/op
                 existUser·p0.999:  9.845 ms/op
                 existUser·p0.9999: 12.395 ms/op
                 existUser·p1.00:   15.876 ms/op

Iteration   2: 2.948 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.797 ms/op
                 existUser·p0.99:   4.522 ms/op
                 existUser·p0.999:  7.606 ms/op
                 existUser·p0.9999: 23.953 ms/op
                 existUser·p1.00:   24.347 ms/op

Iteration   3: 2.952 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.677 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.571 ms/op
                 existUser·p0.999:  8.129 ms/op
                 existUser·p0.9999: 16.011 ms/op
                 existUser·p1.00:   16.466 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 323333
  mean =      2.971 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 44944 
    [ 2.500,  5.000) = 276576 
    [ 5.000,  7.500) = 1302 
    [ 7.500, 10.000) = 305 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.677 ms/op
     p(50.0000) =      2.949 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.830 ms/op
     p(99.0000) =      4.547 ms/op
     p(99.9000) =      8.405 ms/op
     p(99.9900) =     20.387 ms/op
     p(99.9990) =     24.200 ms/op
     p(99.9999) =     24.347 ms/op
    p(100.0000) =     24.347 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.638 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.111 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.116 ±(99.9%) 0.006 ms/op
Iteration   1: 3.069 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.371 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.588 ms/op
                 getUser·p0.95:   3.793 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.848 ms/op
                 getUser·p0.9999: 11.937 ms/op
                 getUser·p1.00:   12.288 ms/op

Iteration   2: 3.051 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.728 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.727 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  6.802 ms/op
                 getUser·p0.9999: 14.698 ms/op
                 getUser·p1.00:   15.008 ms/op

Iteration   3: 3.057 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.518 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.263 ms/op
                 getUser·p0.999:  6.177 ms/op
                 getUser·p0.9999: 26.509 ms/op
                 getUser·p1.00:   26.870 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 313861
  mean =      3.059 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24246 
    [ 2.500,  5.000) = 288632 
    [ 5.000,  7.500) = 728 
    [ 7.500, 10.000) = 63 
    [10.000, 12.500) = 64 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.371 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.604 ms/op
     p(95.0000) =      3.817 ms/op
     p(99.0000) =      4.268 ms/op
     p(99.9000) =      7.004 ms/op
     p(99.9900) =     25.002 ms/op
     p(99.9990) =     26.730 ms/op
     p(99.9999) =     26.870 ms/op
    p(100.0000) =     26.870 ms/op


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
# Warmup Iteration   1: 4.986 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.115 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.042 ±(99.9%) 0.011 ms/op
Iteration   1: 4.129 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.032 ms/op
                 listUser·p0.50:   3.912 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  12.514 ms/op
                 listUser·p0.9999: 14.593 ms/op
                 listUser·p1.00:   14.909 ms/op

Iteration   2: 3.946 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.282 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.366 ms/op
                 listUser·p0.95:   5.349 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  14.008 ms/op
                 listUser·p0.9999: 16.056 ms/op
                 listUser·p1.00:   18.645 ms/op

Iteration   3: 4.025 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.953 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.743 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  14.165 ms/op
                 listUser·p0.9999: 19.237 ms/op
                 listUser·p1.00:   20.152 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 238169
  mean =      4.032 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3748 
    [ 2.500,  5.000) = 205794 
    [ 5.000,  7.500) = 27428 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 271 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.953 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      5.136 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.808 ms/op
     p(99.9000) =     13.566 ms/op
     p(99.9900) =     18.690 ms/op
     p(99.9990) =     19.659 ms/op
     p(99.9999) =     20.152 ms/op
    p(100.0000) =     20.152 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.276 ± 3.011  ops/ms
ClientGrpc.existUser                       thrpt       3  10.748 ± 2.239  ops/ms
ClientGrpc.getUser                         thrpt       3  10.386 ± 3.129  ops/ms
ClientGrpc.listUser                        thrpt       3   7.927 ± 2.511  ops/ms
ClientGrpc.createUser                       avgt       3   3.154 ± 0.446   ms/op
ClientGrpc.existUser                        avgt       3   2.951 ± 0.178   ms/op
ClientGrpc.getUser                          avgt       3   3.073 ± 0.803   ms/op
ClientGrpc.listUser                         avgt       3   4.062 ± 1.667   ms/op
ClientGrpc.createUser                     sample  307325   3.122 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.404           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.043           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.472           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.633           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.776           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.972           ms/op
ClientGrpc.existUser                      sample  323333   2.971 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.677           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.949           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.830           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.547           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.405           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.387           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.347           ms/op
ClientGrpc.getUser                        sample  313861   3.059 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.371           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.817           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.268           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.004           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.002           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.870           ms/op
ClientGrpc.listUser                       sample  238169   4.032 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.953           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.863           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.808           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.566           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.690           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.152           ms/op
