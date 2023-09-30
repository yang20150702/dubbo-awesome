# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.035 ops/ms
# Warmup Iteration   2: 8.576 ops/ms
# Warmup Iteration   3: 9.803 ops/ms
Iteration   1: 9.868 ops/ms
Iteration   2: 10.220 ops/ms
Iteration   3: 10.260 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.116 ±(99.9%) 3.935 ops/ms [Average]
  (min, avg, max) = (9.868, 10.116, 10.260), stdev = 0.216
  CI (99.9%): [6.180, 14.051] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 6.990 ops/ms
# Warmup Iteration   2: 10.233 ops/ms
# Warmup Iteration   3: 10.692 ops/ms
Iteration   1: 10.522 ops/ms
Iteration   2: 10.760 ops/ms
Iteration   3: 10.542 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.608 ±(99.9%) 2.413 ops/ms [Average]
  (min, avg, max) = (10.522, 10.608, 10.760), stdev = 0.132
  CI (99.9%): [8.195, 13.021] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 6.553 ops/ms
# Warmup Iteration   2: 9.720 ops/ms
# Warmup Iteration   3: 10.025 ops/ms
Iteration   1: 10.158 ops/ms
Iteration   2: 10.078 ops/ms
Iteration   3: 10.117 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.118 ±(99.9%) 0.722 ops/ms [Average]
  (min, avg, max) = (10.078, 10.118, 10.158), stdev = 0.040
  CI (99.9%): [9.395, 10.840] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:48
# Fork: 1 of 1
# Warmup Iteration   1: 6.302 ops/ms
# Warmup Iteration   2: 7.387 ops/ms
# Warmup Iteration   3: 7.899 ops/ms
Iteration   1: 7.974 ops/ms
Iteration   2: 8.167 ops/ms
Iteration   3: 8.158 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.100 ±(99.9%) 1.986 ops/ms [Average]
  (min, avg, max) = (7.974, 8.100, 8.167), stdev = 0.109
  CI (99.9%): [6.114, 10.086] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:43
# Fork: 1 of 1
# Warmup Iteration   1: 4.571 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.266 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.155 ±(99.9%) 0.003 ms/op
Iteration   1: 3.170 ±(99.9%) 0.003 ms/op
Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
Iteration   3: 3.099 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.108 ±(99.9%) 1.075 ms/op [Average]
  (min, avg, max) = (3.054, 3.108, 3.170), stdev = 0.059
  CI (99.9%): [2.032, 4.183] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:37
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.110 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.002 ms/op
Iteration   1: 2.936 ±(99.9%) 0.004 ms/op
Iteration   2: 3.049 ±(99.9%) 0.004 ms/op
Iteration   3: 3.043 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.009 ±(99.9%) 1.163 ms/op [Average]
  (min, avg, max) = (2.936, 3.009, 3.049), stdev = 0.064
  CI (99.9%): [1.847, 4.172] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.377 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.202 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.004 ms/op
Iteration   1: 3.175 ±(99.9%) 0.004 ms/op
Iteration   2: 3.092 ±(99.9%) 0.006 ms/op
Iteration   3: 3.155 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.140 ±(99.9%) 0.792 ms/op [Average]
  (min, avg, max) = (3.092, 3.140, 3.175), stdev = 0.043
  CI (99.9%): [2.348, 3.933] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.511 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.110 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.007 ms/op
Iteration   1: 3.975 ±(99.9%) 0.024 ms/op
Iteration   2: 3.961 ±(99.9%) 0.025 ms/op
Iteration   3: 3.937 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.958 ±(99.9%) 0.347 ms/op [Average]
  (min, avg, max) = (3.937, 3.958, 3.975), stdev = 0.019
  CI (99.9%): [3.610, 4.305] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.631 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.268 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.120 ±(99.9%) 0.006 ms/op
Iteration   1: 3.118 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.871 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.834 ms/op
                 createUser·p0.99:   4.415 ms/op
                 createUser·p0.999:  9.011 ms/op
                 createUser·p0.9999: 15.921 ms/op
                 createUser·p1.00:   16.368 ms/op

Iteration   2: 3.149 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.092 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.997 ms/op
                 createUser·p0.999:  13.354 ms/op
                 createUser·p0.9999: 20.049 ms/op
                 createUser·p1.00:   20.185 ms/op

Iteration   3: 3.127 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.307 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.912 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  12.134 ms/op
                 createUser·p0.9999: 16.769 ms/op
                 createUser·p1.00:   18.842 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 306688
  mean =      3.132 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12517 
    [ 2.500,  5.000) = 291821 
    [ 5.000,  7.500) = 1813 
    [ 7.500, 10.000) = 232 
    [10.000, 12.500) = 25 
    [12.500, 15.000) = 171 
    [15.000, 17.500) = 86 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.307 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.867 ms/op
     p(99.0000) =      4.760 ms/op
     p(99.9000) =      9.890 ms/op
     p(99.9900) =     16.586 ms/op
     p(99.9990) =     20.183 ms/op
     p(99.9999) =     20.185 ms/op
    p(100.0000) =     20.185 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 4.251 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.127 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.978 ±(99.9%) 0.007 ms/op
Iteration   1: 3.026 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.717 ms/op
                 existUser·p0.50:   3.002 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.695 ms/op
                 existUser·p0.99:   4.407 ms/op
                 existUser·p0.999:  7.750 ms/op
                 existUser·p0.9999: 17.381 ms/op
                 existUser·p1.00:   20.546 ms/op

Iteration   2: 3.059 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.805 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.588 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  7.999 ms/op
                 existUser·p0.9999: 17.400 ms/op
                 existUser·p1.00:   18.153 ms/op

Iteration   3: 2.930 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.686 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.453 ms/op
                 existUser·p0.95:   3.641 ms/op
                 existUser·p0.99:   4.432 ms/op
                 existUser·p0.999:  8.684 ms/op
                 existUser·p0.9999: 19.664 ms/op
                 existUser·p1.00:   19.792 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 319303
  mean =      3.004 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27711 
    [ 2.500,  5.000) = 289910 
    [ 5.000,  7.500) = 1224 
    [ 7.500, 10.000) = 253 
    [10.000, 12.500) = 53 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 27 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.203 ms/op
     p(99.9900) =     17.400 ms/op
     p(99.9990) =     20.441 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 4.247 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.248 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.240 ±(99.9%) 0.006 ms/op
Iteration   1: 3.204 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.784 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  11.109 ms/op
                 getUser·p0.9999: 21.398 ms/op
                 getUser·p1.00:   24.281 ms/op

Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.969 ms/op
                 getUser·p0.99:   4.571 ms/op
                 getUser·p0.999:  8.574 ms/op
                 getUser·p0.9999: 20.447 ms/op
                 getUser·p1.00:   20.611 ms/op

Iteration   3: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.875 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  9.929 ms/op
                 getUser·p0.9999: 17.101 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301800
  mean =      3.181 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10040 
    [ 2.500,  5.000) = 289558 
    [ 5.000,  7.500) = 1674 
    [ 7.500, 10.000) = 229 
    [10.000, 12.500) = 79 
    [12.500, 15.000) = 78 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 26 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.702 ms/op
     p(99.9000) =      9.932 ms/op
     p(99.9900) =     20.349 ms/op
     p(99.9990) =     24.214 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.579 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.123 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.982 ±(99.9%) 0.012 ms/op
Iteration   1: 3.979 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.313 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.325 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.342 ms/op
                 listUser·p0.9999: 17.595 ms/op
                 listUser·p1.00:   17.727 ms/op

Iteration   2: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.409 ms/op
                 listUser·p0.50:   3.809 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  13.902 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.480 ms/op

Iteration   3: 4.009 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.163 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.981 ms/op
                 listUser·p0.95:   5.972 ms/op
                 listUser·p0.99:   6.906 ms/op
                 listUser·p0.999:  15.483 ms/op
                 listUser·p0.9999: 25.430 ms/op
                 listUser·p1.00:   26.083 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 242079
  mean =      3.967 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2943 
    [ 2.500,  5.000) = 221448 
    [ 5.000,  7.500) = 16415 
    [ 7.500, 10.000) = 703 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 260 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 8 

  Percentiles, ms/op:
      p(0.0000) =      1.163 ms/op
     p(50.0000) =      3.854 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      5.628 ms/op
     p(99.0000) =      6.799 ms/op
     p(99.9000) =     14.482 ms/op
     p(99.9900) =     22.931 ms/op
     p(99.9990) =     25.944 ms/op
     p(99.9999) =     26.083 ms/op
    p(100.0000) =     26.083 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.116 ± 3.935  ops/ms
ClientGrpc.existUser                       thrpt       3  10.608 ± 2.413  ops/ms
ClientGrpc.getUser                         thrpt       3  10.118 ± 0.722  ops/ms
ClientGrpc.listUser                        thrpt       3   8.100 ± 1.986  ops/ms
ClientGrpc.createUser                       avgt       3   3.108 ± 1.075   ms/op
ClientGrpc.existUser                        avgt       3   3.009 ± 1.163   ms/op
ClientGrpc.getUser                          avgt       3   3.140 ± 0.792   ms/op
ClientGrpc.listUser                         avgt       3   3.958 ± 0.347   ms/op
ClientGrpc.createUser                     sample  306688   3.132 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.307           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.682           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.867           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.760           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.890           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.586           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.185           ms/op
ClientGrpc.existUser                      sample  319303   3.004 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.686           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.535           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.203           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.400           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.546           ms/op
ClientGrpc.getUser                        sample  301800   3.181 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.730           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.777           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.702           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.932           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.349           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.281           ms/op
ClientGrpc.listUser                       sample  242079   3.967 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.163           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.854           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.628           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.799           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.482           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.931           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.083           ms/op
