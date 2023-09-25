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
# Warmup Iteration   1: 4.654 ops/ms
# Warmup Iteration   2: 8.917 ops/ms
# Warmup Iteration   3: 9.832 ops/ms
Iteration   1: 10.089 ops/ms
Iteration   2: 10.359 ops/ms
Iteration   3: 10.108 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.185 ±(99.9%) 2.747 ops/ms [Average]
  (min, avg, max) = (10.089, 10.185, 10.359), stdev = 0.151
  CI (99.9%): [7.438, 12.932] (assumes normal distribution)


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
# Warmup Iteration   1: 7.467 ops/ms
# Warmup Iteration   2: 10.513 ops/ms
# Warmup Iteration   3: 10.804 ops/ms
Iteration   1: 10.523 ops/ms
Iteration   2: 10.916 ops/ms
Iteration   3: 11.091 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.844 ±(99.9%) 5.307 ops/ms [Average]
  (min, avg, max) = (10.523, 10.844, 11.091), stdev = 0.291
  CI (99.9%): [5.537, 16.150] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 7.284 ops/ms
# Warmup Iteration   2: 9.836 ops/ms
# Warmup Iteration   3: 10.001 ops/ms
Iteration   1: 10.115 ops/ms
Iteration   2: 10.301 ops/ms
Iteration   3: 10.248 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.221 ±(99.9%) 1.742 ops/ms [Average]
  (min, avg, max) = (10.115, 10.221, 10.301), stdev = 0.096
  CI (99.9%): [8.479, 11.964] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.706 ops/ms
# Warmup Iteration   2: 8.162 ops/ms
# Warmup Iteration   3: 8.275 ops/ms
Iteration   1: 8.399 ops/ms
Iteration   2: 8.456 ops/ms
Iteration   3: 8.418 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.424 ±(99.9%) 0.525 ops/ms [Average]
  (min, avg, max) = (8.399, 8.424, 8.456), stdev = 0.029
  CI (99.9%): [7.899, 8.949] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:42
# Fork: 1 of 1
# Warmup Iteration   1: 3.957 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.272 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.002 ms/op
Iteration   1: 3.234 ±(99.9%) 0.003 ms/op
Iteration   2: 3.210 ±(99.9%) 0.006 ms/op
Iteration   3: 3.206 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.216 ±(99.9%) 0.276 ms/op [Average]
  (min, avg, max) = (3.206, 3.216, 3.234), stdev = 0.015
  CI (99.9%): [2.941, 3.492] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.684 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.155 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.053 ±(99.9%) 0.002 ms/op
Iteration   1: 2.982 ±(99.9%) 0.004 ms/op
Iteration   2: 3.047 ±(99.9%) 0.002 ms/op
Iteration   3: 2.927 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.985 ±(99.9%) 1.098 ms/op [Average]
  (min, avg, max) = (2.927, 2.985, 3.047), stdev = 0.060
  CI (99.9%): [1.887, 4.083] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.081 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.231 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.159 ±(99.9%) 0.002 ms/op
Iteration   1: 3.102 ±(99.9%) 0.002 ms/op
Iteration   2: 3.115 ±(99.9%) 0.002 ms/op
Iteration   3: 3.176 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.131 ±(99.9%) 0.726 ms/op [Average]
  (min, avg, max) = (3.102, 3.131, 3.176), stdev = 0.040
  CI (99.9%): [2.405, 3.857] (assumes normal distribution)


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
# Warmup Iteration   1: 5.277 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.124 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.880 ±(99.9%) 0.015 ms/op
Iteration   1: 3.856 ±(99.9%) 0.036 ms/op
Iteration   2: 3.785 ±(99.9%) 0.054 ms/op
Iteration   3: 3.831 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.824 ±(99.9%) 0.658 ms/op [Average]
  (min, avg, max) = (3.785, 3.824, 3.856), stdev = 0.036
  CI (99.9%): [3.166, 4.482] (assumes normal distribution)


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
# Warmup Iteration   1: 4.124 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.184 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.494 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.666 ms/op
                 createUser·p0.95:   3.867 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  10.551 ms/op
                 createUser·p0.9999: 14.140 ms/op
                 createUser·p1.00:   17.138 ms/op

Iteration   2: 3.105 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.797 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.785 ms/op
                 createUser·p0.99:   4.440 ms/op
                 createUser·p0.999:  7.947 ms/op
                 createUser·p0.9999: 13.037 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   3: 3.131 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.732 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   4.686 ms/op
                 createUser·p0.999:  8.012 ms/op
                 createUser·p0.9999: 14.834 ms/op
                 createUser·p1.00:   16.777 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308106
  mean =      3.113 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 708 
    [ 1.250,  2.500) = 11267 
    [ 2.500,  3.750) = 272878 
    [ 3.750,  5.000) = 21177 
    [ 5.000,  6.250) = 1272 
    [ 6.250,  7.500) = 370 
    [ 7.500,  8.750) = 87 
    [ 8.750, 10.000) = 68 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 115 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 5 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.494 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.662 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.612 ms/op
     p(99.9000) =      9.632 ms/op
     p(99.9900) =     14.418 ms/op
     p(99.9990) =     16.727 ms/op
     p(99.9999) =     17.138 ms/op
    p(100.0000) =     17.138 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.803 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
Iteration   1: 3.016 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.769 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.699 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.757 ms/op
                 existUser·p0.9999: 13.763 ms/op
                 existUser·p1.00:   14.025 ms/op

Iteration   2: 3.060 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.690 ms/op
                 existUser·p0.99:   4.039 ms/op
                 existUser·p0.999:  8.511 ms/op
                 existUser·p0.9999: 15.181 ms/op
                 existUser·p1.00:   15.565 ms/op

Iteration   3: 3.012 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.740 ms/op
                 existUser·p0.50:   2.961 ms/op
                 existUser·p0.90:   3.482 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.145 ms/op
                 existUser·p0.999:  9.126 ms/op
                 existUser·p0.9999: 23.638 ms/op
                 existUser·p1.00:   23.953 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 316699
  mean =      3.029 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13675 
    [ 2.500,  5.000) = 301754 
    [ 5.000,  7.500) = 864 
    [ 7.500, 10.000) = 210 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 18 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.740 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.527 ms/op
     p(95.0000) =      3.695 ms/op
     p(99.0000) =      4.121 ms/op
     p(99.9000) =      8.520 ms/op
     p(99.9900) =     21.605 ms/op
     p(99.9990) =     23.871 ms/op
     p(99.9999) =     23.953 ms/op
    p(100.0000) =     23.953 ms/op


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
# Warmup Iteration   1: 3.981 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.204 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.100 ±(99.9%) 0.007 ms/op
Iteration   1: 3.125 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.804 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.916 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  9.617 ms/op
                 getUser·p0.9999: 13.153 ms/op
                 getUser·p1.00:   13.615 ms/op

Iteration   2: 3.073 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.762 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.711 ms/op
                 getUser·p0.99:   4.235 ms/op
                 getUser·p0.999:  6.808 ms/op
                 getUser·p0.9999: 14.290 ms/op
                 getUser·p1.00:   14.598 ms/op

Iteration   3: 3.126 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.478 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.637 ms/op
                 getUser·p0.95:   3.777 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  9.045 ms/op
                 getUser·p0.9999: 15.717 ms/op
                 getUser·p1.00:   16.056 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308861
  mean =      3.108 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 634 
    [ 1.250,  2.500) = 12307 
    [ 2.500,  3.750) = 276545 
    [ 3.750,  5.000) = 17854 
    [ 5.000,  6.250) = 737 
    [ 6.250,  7.500) = 343 
    [ 7.500,  8.750) = 151 
    [ 8.750, 10.000) = 128 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 1 
    [12.500, 13.750) = 38 
    [13.750, 15.000) = 60 
    [15.000, 16.250) = 29 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.478 ms/op
     p(50.0000) =      3.080 ms/op
     p(90.0000) =      3.637 ms/op
     p(95.0000) =      3.805 ms/op
     p(99.0000) =      4.366 ms/op
     p(99.9000) =      8.487 ms/op
     p(99.9900) =     14.942 ms/op
     p(99.9990) =     15.971 ms/op
     p(99.9999) =     16.056 ms/op
    p(100.0000) =     16.056 ms/op


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
# Warmup Iteration   1: 4.767 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.860 ±(99.9%) 0.010 ms/op
Iteration   1: 3.848 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.976 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.177 ms/op
                 listUser·p0.99:   6.455 ms/op
                 listUser·p0.999:  16.085 ms/op
                 listUser·p0.9999: 18.799 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   2: 3.734 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   3.650 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.923 ms/op
                 listUser·p0.99:   6.488 ms/op
                 listUser·p0.999:  13.212 ms/op
                 listUser·p0.9999: 15.972 ms/op
                 listUser·p1.00:   18.842 ms/op

Iteration   3: 3.834 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.899 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.169 ms/op
                 listUser·p0.99:   6.472 ms/op
                 listUser·p0.999:  14.650 ms/op
                 listUser·p0.9999: 17.913 ms/op
                 listUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 252207
  mean =      3.804 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3160 
    [ 2.500,  5.000) = 235188 
    [ 5.000,  7.500) = 12959 
    [ 7.500, 10.000) = 399 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 184 
    [15.000, 17.500) = 156 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.899 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.293 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      6.472 ms/op
     p(99.9000) =     14.467 ms/op
     p(99.9900) =     18.179 ms/op
     p(99.9990) =     20.101 ms/op
     p(99.9999) =     21.529 ms/op
    p(100.0000) =     21.529 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.185 ± 2.747  ops/ms
ClientGrpc.existUser                       thrpt       3  10.844 ± 5.307  ops/ms
ClientGrpc.getUser                         thrpt       3  10.221 ± 1.742  ops/ms
ClientGrpc.listUser                        thrpt       3   8.424 ± 0.525  ops/ms
ClientGrpc.createUser                       avgt       3   3.216 ± 0.276   ms/op
ClientGrpc.existUser                        avgt       3   2.985 ± 1.098   ms/op
ClientGrpc.getUser                          avgt       3   3.131 ± 0.726   ms/op
ClientGrpc.listUser                         avgt       3   3.824 ± 0.658   ms/op
ClientGrpc.createUser                     sample  308106   3.113 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.494           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.068           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.612           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.632           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.418           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.138           ms/op
ClientGrpc.existUser                      sample  316699   3.029 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.740           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.986           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.527           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.695           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.121           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.520           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.605           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          23.953           ms/op
ClientGrpc.getUser                        sample  308861   3.108 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.478           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.080           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.805           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.366           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.487           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          14.942           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          16.056           ms/op
ClientGrpc.listUser                       sample  252207   3.804 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.899           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.711           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.293           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.104           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.467           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.179           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.529           ms/op
