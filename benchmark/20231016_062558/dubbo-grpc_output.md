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
# Warmup Iteration   1: 3.841 ops/ms
# Warmup Iteration   2: 8.780 ops/ms
# Warmup Iteration   3: 9.775 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.238 ops/ms
Iteration   3: 10.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.201 ±(99.9%) 1.617 ops/ms [Average]
  (min, avg, max) = (10.100, 10.201, 10.266), stdev = 0.089
  CI (99.9%): [8.584, 11.819] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.064 ops/ms
# Warmup Iteration   2: 10.474 ops/ms
# Warmup Iteration   3: 10.585 ops/ms
Iteration   1: 10.564 ops/ms
Iteration   2: 10.702 ops/ms
Iteration   3: 10.784 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.683 ±(99.9%) 2.033 ops/ms [Average]
  (min, avg, max) = (10.564, 10.683, 10.784), stdev = 0.111
  CI (99.9%): [8.650, 12.716] (assumes normal distribution)


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
# Warmup Iteration   1: 6.587 ops/ms
# Warmup Iteration   2: 9.879 ops/ms
# Warmup Iteration   3: 10.057 ops/ms
Iteration   1: 10.087 ops/ms
Iteration   2: 10.188 ops/ms
Iteration   3: 10.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.115 ±(99.9%) 1.167 ops/ms [Average]
  (min, avg, max) = (10.070, 10.115, 10.188), stdev = 0.064
  CI (99.9%): [8.949, 11.282] (assumes normal distribution)


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
# Warmup Iteration   1: 5.632 ops/ms
# Warmup Iteration   2: 7.647 ops/ms
# Warmup Iteration   3: 7.947 ops/ms
Iteration   1: 7.963 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 7.941 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.946 ±(99.9%) 0.274 ops/ms [Average]
  (min, avg, max) = (7.934, 7.946, 7.963), stdev = 0.015
  CI (99.9%): [7.672, 8.220] (assumes normal distribution)


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
# Warmup Iteration   1: 4.401 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.315 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.002 ms/op
Iteration   1: 3.167 ±(99.9%) 0.003 ms/op
Iteration   2: 3.188 ±(99.9%) 0.004 ms/op
Iteration   3: 3.170 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.175 ±(99.9%) 0.211 ms/op [Average]
  (min, avg, max) = (3.167, 3.175, 3.188), stdev = 0.012
  CI (99.9%): [2.964, 3.386] (assumes normal distribution)


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
# Warmup Iteration   1: 4.214 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.093 ±(99.9%) 0.003 ms/op
Iteration   1: 3.028 ±(99.9%) 0.003 ms/op
Iteration   2: 2.997 ±(99.9%) 0.002 ms/op
Iteration   3: 3.005 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.010 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (2.997, 3.010, 3.028), stdev = 0.016
  CI (99.9%): [2.714, 3.306] (assumes normal distribution)


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
# Warmup Iteration   1: 4.421 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.237 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.004 ms/op
Iteration   1: 3.194 ±(99.9%) 0.005 ms/op
Iteration   2: 3.112 ±(99.9%) 0.003 ms/op
Iteration   3: 3.143 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.150 ±(99.9%) 0.760 ms/op [Average]
  (min, avg, max) = (3.112, 3.150, 3.194), stdev = 0.042
  CI (99.9%): [2.389, 3.910] (assumes normal distribution)


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
# Warmup Iteration   1: 5.690 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 4.058 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.864 ±(99.9%) 0.014 ms/op
Iteration   1: 3.995 ±(99.9%) 0.027 ms/op
Iteration   2: 3.775 ±(99.9%) 0.005 ms/op
Iteration   3: 4.019 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.930 ±(99.9%) 2.451 ms/op [Average]
  (min, avg, max) = (3.775, 3.930, 4.019), stdev = 0.134
  CI (99.9%): [1.479, 6.380] (assumes normal distribution)


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
# Warmup Iteration   1: 4.416 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.281 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.172 ±(99.9%) 0.007 ms/op
Iteration   1: 3.133 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.963 ms/op
                 createUser·p0.50:   3.084 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.702 ms/op
                 createUser·p0.999:  11.256 ms/op
                 createUser·p0.9999: 24.168 ms/op
                 createUser·p1.00:   25.428 ms/op

Iteration   2: 3.192 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.428 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.961 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  8.207 ms/op
                 createUser·p0.9999: 21.758 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   3: 3.143 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.776 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.723 ms/op
                 createUser·p0.95:   3.908 ms/op
                 createUser·p0.99:   4.456 ms/op
                 createUser·p0.999:  11.714 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 304118
  mean =      3.156 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10542 
    [ 2.500,  5.000) = 291596 
    [ 5.000,  7.500) = 1504 
    [ 7.500, 10.000) = 140 
    [10.000, 12.500) = 84 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.428 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.908 ms/op
     p(99.0000) =      4.512 ms/op
     p(99.9000) =     11.076 ms/op
     p(99.9900) =     21.613 ms/op
     p(99.9990) =     25.391 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 4.120 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.090 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
Iteration   1: 3.023 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.751 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.152 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   21.692 ms/op

Iteration   2: 2.959 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.743 ms/op
                 existUser·p0.999:  9.110 ms/op
                 existUser·p0.9999: 14.405 ms/op
                 existUser·p1.00:   15.401 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.684 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.731 ms/op
                 existUser·p0.99:   4.669 ms/op
                 existUser·p0.999:  10.403 ms/op
                 existUser·p0.9999: 18.732 ms/op
                 existUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320626
  mean =      2.994 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26544 
    [ 2.500,  5.000) = 292283 
    [ 5.000,  7.500) = 1324 
    [ 7.500, 10.000) = 196 
    [10.000, 12.500) = 89 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 45 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.684 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.498 ms/op
     p(95.0000) =      3.719 ms/op
     p(99.0000) =      4.620 ms/op
     p(99.9000) =      9.296 ms/op
     p(99.9900) =     18.612 ms/op
     p(99.9990) =     21.529 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.432 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.219 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
Iteration   1: 3.073 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.873 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.484 ms/op
                 getUser·p0.95:   3.674 ms/op
                 getUser·p0.99:   4.678 ms/op
                 getUser·p0.999:  8.984 ms/op
                 getUser·p0.9999: 12.520 ms/op
                 getUser·p1.00:   12.763 ms/op

Iteration   2: 3.171 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.743 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.723 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.694 ms/op
                 getUser·p0.999:  7.725 ms/op
                 getUser·p0.9999: 14.430 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.617 ms/op
                 getUser·p0.95:   3.768 ms/op
                 getUser·p0.99:   4.817 ms/op
                 getUser·p0.999:  8.569 ms/op
                 getUser·p0.9999: 17.818 ms/op
                 getUser·p1.00:   18.285 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307559
  mean =      3.122 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 327 
    [ 1.250,  2.500) = 8714 
    [ 2.500,  3.750) = 279491 
    [ 3.750,  5.000) = 16750 
    [ 5.000,  6.250) = 1311 
    [ 6.250,  7.500) = 545 
    [ 7.500,  8.750) = 147 
    [ 8.750, 10.000) = 46 
    [10.000, 11.250) = 20 
    [11.250, 12.500) = 68 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 64 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 5 
    [17.500, 18.750) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.609 ms/op
     p(95.0000) =      3.809 ms/op
     p(99.0000) =      4.735 ms/op
     p(99.9000) =      8.429 ms/op
     p(99.9900) =     15.737 ms/op
     p(99.9990) =     18.149 ms/op
     p(99.9999) =     18.285 ms/op
    p(100.0000) =     18.285 ms/op


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
# Warmup Iteration   1: 5.947 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.086 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.996 ±(99.9%) 0.012 ms/op
Iteration   1: 4.043 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.007 ms/op
                 listUser·p0.50:   3.903 ms/op
                 listUser·p0.90:   4.661 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.184 ms/op
                 listUser·p0.999:  14.102 ms/op
                 listUser·p0.9999: 18.225 ms/op
                 listUser·p1.00:   20.447 ms/op

Iteration   2: 3.946 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.368 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   5.292 ms/op
                 listUser·p0.99:   6.898 ms/op
                 listUser·p0.999:  14.072 ms/op
                 listUser·p0.9999: 15.301 ms/op
                 listUser·p1.00:   16.417 ms/op

Iteration   3: 3.946 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.980 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   5.276 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.645 ms/op
                 listUser·p0.9999: 18.147 ms/op
                 listUser·p1.00:   19.857 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 241293
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2003 
    [ 2.500,  5.000) = 223386 
    [ 5.000,  7.500) = 14576 
    [ 7.500, 10.000) = 737 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 343 
    [15.000, 17.500) = 99 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.368 ms/op
     p(50.0000) =      3.867 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.546 ms/op
     p(99.0000) =      6.906 ms/op
     p(99.9000) =     14.254 ms/op
     p(99.9900) =     18.051 ms/op
     p(99.9990) =     20.355 ms/op
     p(99.9999) =     20.447 ms/op
    p(100.0000) =     20.447 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.201 ± 1.617  ops/ms
ClientGrpc.existUser                       thrpt       3  10.683 ± 2.033  ops/ms
ClientGrpc.getUser                         thrpt       3  10.115 ± 1.167  ops/ms
ClientGrpc.listUser                        thrpt       3   7.946 ± 0.274  ops/ms
ClientGrpc.createUser                       avgt       3   3.175 ± 0.211   ms/op
ClientGrpc.existUser                        avgt       3   3.010 ± 0.296   ms/op
ClientGrpc.getUser                          avgt       3   3.150 ± 0.760   ms/op
ClientGrpc.listUser                         avgt       3   3.930 ± 2.451   ms/op
ClientGrpc.createUser                     sample  304118   3.156 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.428           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.109           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.908           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.512           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.076           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.613           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.935           ms/op
ClientGrpc.existUser                      sample  320626   2.994 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.684           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.719           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.620           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.296           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          18.612           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.692           ms/op
ClientGrpc.getUser                        sample  307559   3.122 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.076           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.609           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.735           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.429           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.737           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.285           ms/op
ClientGrpc.listUser                       sample  241293   3.978 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.368           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.867           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.546           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.254           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.051           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.447           ms/op
