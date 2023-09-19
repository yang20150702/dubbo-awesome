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
# Warmup Iteration   1: 3.436 ops/ms
# Warmup Iteration   2: 7.682 ops/ms
# Warmup Iteration   3: 9.061 ops/ms
Iteration   1: 9.343 ops/ms
Iteration   2: 9.728 ops/ms
Iteration   3: 9.525 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.532 ±(99.9%) 3.515 ops/ms [Average]
  (min, avg, max) = (9.343, 9.532, 9.728), stdev = 0.193
  CI (99.9%): [6.017, 13.047] (assumes normal distribution)


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
# Warmup Iteration   1: 6.752 ops/ms
# Warmup Iteration   2: 9.918 ops/ms
# Warmup Iteration   3: 10.365 ops/ms
Iteration   1: 10.535 ops/ms
Iteration   2: 10.313 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.431 ±(99.9%) 2.034 ops/ms [Average]
  (min, avg, max) = (10.313, 10.431, 10.535), stdev = 0.111
  CI (99.9%): [8.397, 12.465] (assumes normal distribution)


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
# Warmup Iteration   1: 6.248 ops/ms
# Warmup Iteration   2: 9.398 ops/ms
# Warmup Iteration   3: 9.788 ops/ms
Iteration   1: 9.684 ops/ms
Iteration   2: 9.984 ops/ms
Iteration   3: 9.889 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.852 ±(99.9%) 2.796 ops/ms [Average]
  (min, avg, max) = (9.684, 9.852, 9.984), stdev = 0.153
  CI (99.9%): [7.056, 12.648] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 5.101 ops/ms
# Warmup Iteration   2: 7.498 ops/ms
# Warmup Iteration   3: 7.626 ops/ms
Iteration   1: 7.833 ops/ms
Iteration   2: 7.997 ops/ms
Iteration   3: 7.692 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.841 ±(99.9%) 2.784 ops/ms [Average]
  (min, avg, max) = (7.692, 7.841, 7.997), stdev = 0.153
  CI (99.9%): [5.056, 10.625] (assumes normal distribution)


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
# Warmup Iteration   1: 4.587 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.390 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.316 ±(99.9%) 0.001 ms/op
Iteration   1: 3.286 ±(99.9%) 0.002 ms/op
Iteration   2: 3.180 ±(99.9%) 0.003 ms/op
Iteration   3: 3.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.214 ±(99.9%) 1.145 ms/op [Average]
  (min, avg, max) = (3.176, 3.214, 3.286), stdev = 0.063
  CI (99.9%): [2.069, 4.359] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.565 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.125 ±(99.9%) 0.003 ms/op
Iteration   1: 3.101 ±(99.9%) 0.001 ms/op
Iteration   2: 3.013 ±(99.9%) 0.002 ms/op
Iteration   3: 3.007 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.040 ±(99.9%) 0.958 ms/op [Average]
  (min, avg, max) = (3.007, 3.040, 3.101), stdev = 0.053
  CI (99.9%): [2.082, 3.999] (assumes normal distribution)


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
# Warmup Iteration   1: 4.365 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.388 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.235 ±(99.9%) 0.003 ms/op
Iteration   1: 3.187 ±(99.9%) 0.002 ms/op
Iteration   2: 3.230 ±(99.9%) 0.003 ms/op
Iteration   3: 3.193 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.203 ±(99.9%) 0.425 ms/op [Average]
  (min, avg, max) = (3.187, 3.203, 3.230), stdev = 0.023
  CI (99.9%): [2.778, 3.629] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.079 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.368 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.150 ±(99.9%) 0.008 ms/op
Iteration   1: 4.156 ±(99.9%) 0.012 ms/op
Iteration   2: 4.015 ±(99.9%) 0.014 ms/op
Iteration   3: 4.067 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.080 ±(99.9%) 1.301 ms/op [Average]
  (min, avg, max) = (4.015, 4.080, 4.156), stdev = 0.071
  CI (99.9%): [2.779, 5.380] (assumes normal distribution)


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
# Warmup Iteration   1: 4.867 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.424 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.269 ±(99.9%) 0.007 ms/op
Iteration   1: 3.237 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.869 ms/op
                 createUser·p0.50:   3.199 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.169 ms/op
                 createUser·p0.9999: 13.588 ms/op
                 createUser·p1.00:   13.894 ms/op

Iteration   2: 3.193 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.840 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.703 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   5.038 ms/op
                 createUser·p0.999:  9.271 ms/op
                 createUser·p0.9999: 15.516 ms/op
                 createUser·p1.00:   15.974 ms/op

Iteration   3: 3.255 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.652 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.981 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   5.251 ms/op
                 createUser·p0.999:  11.522 ms/op
                 createUser·p0.9999: 18.186 ms/op
                 createUser·p1.00:   18.481 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 297165
  mean =      3.228 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 475 
    [ 1.250,  2.500) = 9395 
    [ 2.500,  3.750) = 249959 
    [ 3.750,  5.000) = 34238 
    [ 5.000,  6.250) = 1793 
    [ 6.250,  7.500) = 758 
    [ 7.500,  8.750) = 190 
    [ 8.750, 10.000) = 88 
    [10.000, 11.250) = 50 
    [11.250, 12.500) = 54 
    [12.500, 13.750) = 32 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 56 
    [16.250, 17.500) = 9 
    [17.500, 18.750) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.652 ms/op
     p(50.0000) =      3.170 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.055 ms/op
     p(99.0000) =      5.046 ms/op
     p(99.9000) =      9.454 ms/op
     p(99.9900) =     17.727 ms/op
     p(99.9990) =     18.350 ms/op
     p(99.9999) =     18.481 ms/op
    p(100.0000) =     18.481 ms/op


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
# Warmup Iteration   1: 4.385 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.007 ms/op
Iteration   1: 3.062 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.398 ms/op
                 existUser·p0.50:   3.006 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.674 ms/op
                 existUser·p0.99:   4.604 ms/op
                 existUser·p0.999:  9.119 ms/op
                 existUser·p0.9999: 29.954 ms/op
                 existUser·p1.00:   30.540 ms/op

Iteration   2: 3.096 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.896 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   4.596 ms/op
                 existUser·p0.999:  7.438 ms/op
                 existUser·p0.9999: 25.231 ms/op
                 existUser·p1.00:   25.330 ms/op

Iteration   3: 3.076 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.741 ms/op
                 existUser·p0.50:   3.031 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.871 ms/op
                 existUser·p0.99:   4.817 ms/op
                 existUser·p0.999:  8.168 ms/op
                 existUser·p0.9999: 27.853 ms/op
                 existUser·p1.00:   28.049 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311782
  mean =      3.078 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16798 
    [ 2.500,  5.000) = 292547 
    [ 5.000,  7.500) = 1961 
    [ 7.500, 10.000) = 301 
    [10.000, 12.500) = 15 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 8 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.398 ms/op
     p(50.0000) =      3.027 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.678 ms/op
     p(99.9000) =      8.136 ms/op
     p(99.9900) =     27.350 ms/op
     p(99.9990) =     30.307 ms/op
     p(99.9999) =     30.540 ms/op
    p(100.0000) =     30.540 ms/op


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
# Warmup Iteration   1: 4.674 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.433 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.007 ms/op
Iteration   1: 3.209 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.838 ms/op
                 getUser·p0.50:   3.150 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.853 ms/op
                 getUser·p0.999:  8.433 ms/op
                 getUser·p0.9999: 18.154 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.214 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.668 ms/op
                 getUser·p0.50:   3.154 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  9.135 ms/op
                 getUser·p0.9999: 19.990 ms/op
                 getUser·p1.00:   20.513 ms/op

Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.948 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.764 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   4.858 ms/op
                 getUser·p0.999:  8.858 ms/op
                 getUser·p0.9999: 21.589 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 300051
  mean =      3.199 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7001 
    [ 2.500,  5.000) = 290576 
    [ 5.000,  7.500) = 1923 
    [ 7.500, 10.000) = 300 
    [10.000, 12.500) = 67 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 39 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.668 ms/op
     p(50.0000) =      3.138 ms/op
     p(90.0000) =      3.752 ms/op
     p(95.0000) =      3.961 ms/op
     p(99.0000) =      4.801 ms/op
     p(99.9000) =      8.650 ms/op
     p(99.9900) =     20.152 ms/op
     p(99.9990) =     21.660 ms/op
     p(99.9999) =     21.758 ms/op
    p(100.0000) =     21.758 ms/op


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
# Warmup Iteration   1: 5.767 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 4.264 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.064 ±(99.9%) 0.011 ms/op
Iteration   1: 4.023 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.579 ms/op
                 listUser·p0.95:   5.382 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 15.779 ms/op
                 listUser·p1.00:   16.155 ms/op

Iteration   2: 4.154 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.192 ms/op
                 listUser·p0.50:   3.969 ms/op
                 listUser·p0.90:   5.186 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.463 ms/op
                 listUser·p0.999:  16.612 ms/op
                 listUser·p0.9999: 19.212 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 4.204 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.126 ms/op
                 listUser·p0.50:   4.010 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.038 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  17.267 ms/op
                 listUser·p0.9999: 22.164 ms/op
                 listUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232652
  mean =      4.126 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1307 
    [ 2.500,  5.000) = 207378 
    [ 5.000,  7.500) = 22008 
    [ 7.500, 10.000) = 1363 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 175 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 4 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.126 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      5.046 ms/op
     p(95.0000) =      5.874 ms/op
     p(99.0000) =      7.283 ms/op
     p(99.9000) =     15.499 ms/op
     p(99.9900) =     20.863 ms/op
     p(99.9990) =     22.577 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.532 ± 3.515  ops/ms
ClientGrpc.existUser                       thrpt       3  10.431 ± 2.034  ops/ms
ClientGrpc.getUser                         thrpt       3   9.852 ± 2.796  ops/ms
ClientGrpc.listUser                        thrpt       3   7.841 ± 2.784  ops/ms
ClientGrpc.createUser                       avgt       3   3.214 ± 1.145   ms/op
ClientGrpc.existUser                        avgt       3   3.040 ± 0.958   ms/op
ClientGrpc.getUser                          avgt       3   3.203 ± 0.425   ms/op
ClientGrpc.listUser                         avgt       3   4.080 ± 1.301   ms/op
ClientGrpc.createUser                     sample  297165   3.228 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.652           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.170           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.830           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.055           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.046           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.727           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.481           ms/op
ClientGrpc.existUser                      sample  311782   3.078 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.398           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.027           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.801           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.136           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.350           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          30.540           ms/op
ClientGrpc.getUser                        sample  300051   3.199 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.668           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.138           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.752           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.961           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.801           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.650           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.152           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          21.758           ms/op
ClientGrpc.listUser                       sample  232652   4.126 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.126           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.965           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.874           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.283           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.499           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.863           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.643           ms/op
