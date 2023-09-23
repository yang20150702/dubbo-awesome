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
# Warmup Iteration   1: 4.248 ops/ms
# Warmup Iteration   2: 9.089 ops/ms
# Warmup Iteration   3: 9.825 ops/ms
Iteration   1: 10.438 ops/ms
Iteration   2: 10.202 ops/ms
Iteration   3: 10.269 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.303 ±(99.9%) 2.216 ops/ms [Average]
  (min, avg, max) = (10.202, 10.303, 10.438), stdev = 0.121
  CI (99.9%): [8.087, 12.519] (assumes normal distribution)


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
# Warmup Iteration   1: 7.346 ops/ms
# Warmup Iteration   2: 10.561 ops/ms
# Warmup Iteration   3: 10.700 ops/ms
Iteration   1: 11.235 ops/ms
Iteration   2: 10.734 ops/ms
Iteration   3: 10.818 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.929 ±(99.9%) 4.898 ops/ms [Average]
  (min, avg, max) = (10.734, 10.929, 11.235), stdev = 0.268
  CI (99.9%): [6.031, 15.827] (assumes normal distribution)


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
# Warmup Iteration   1: 6.769 ops/ms
# Warmup Iteration   2: 9.952 ops/ms
# Warmup Iteration   3: 10.293 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.281 ops/ms
Iteration   3: 10.496 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.408 ±(99.9%) 2.049 ops/ms [Average]
  (min, avg, max) = (10.281, 10.408, 10.496), stdev = 0.112
  CI (99.9%): [8.360, 12.457] (assumes normal distribution)


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
# Warmup Iteration   1: 5.220 ops/ms
# Warmup Iteration   2: 7.871 ops/ms
# Warmup Iteration   3: 8.053 ops/ms
Iteration   1: 8.228 ops/ms
Iteration   2: 8.770 ops/ms
Iteration   3: 8.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.375 ±(99.9%) 6.302 ops/ms [Average]
  (min, avg, max) = (8.128, 8.375, 8.770), stdev = 0.345
  CI (99.9%): [2.073, 14.677] (assumes normal distribution)


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
# Warmup Iteration   1: 4.359 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.247 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.110 ±(99.9%) 0.002 ms/op
Iteration   1: 3.124 ±(99.9%) 0.003 ms/op
Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
Iteration   3: 3.076 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.084 ±(99.9%) 0.656 ms/op [Average]
  (min, avg, max) = (3.053, 3.084, 3.124), stdev = 0.036
  CI (99.9%): [2.428, 3.741] (assumes normal distribution)


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
# Warmup Iteration   1: 3.877 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.000 ±(99.9%) 0.002 ms/op
Iteration   1: 2.927 ±(99.9%) 0.003 ms/op
Iteration   2: 2.986 ±(99.9%) 0.002 ms/op
Iteration   3: 3.014 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.976 ±(99.9%) 0.807 ms/op [Average]
  (min, avg, max) = (2.927, 2.976, 3.014), stdev = 0.044
  CI (99.9%): [2.169, 3.782] (assumes normal distribution)


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
# Warmup Iteration   1: 4.249 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.188 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.134 ±(99.9%) 0.001 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.053 ±(99.9%) 0.002 ms/op
Iteration   3: 3.100 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.092 ±(99.9%) 0.643 ms/op [Average]
  (min, avg, max) = (3.053, 3.092, 3.122), stdev = 0.035
  CI (99.9%): [2.449, 3.735] (assumes normal distribution)


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
# Warmup Iteration   1: 5.245 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.079 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.972 ±(99.9%) 0.024 ms/op
Iteration   1: 3.860 ±(99.9%) 0.006 ms/op
Iteration   2: 3.840 ±(99.9%) 0.019 ms/op
Iteration   3: 3.899 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.866 ±(99.9%) 0.556 ms/op [Average]
  (min, avg, max) = (3.840, 3.866, 3.899), stdev = 0.030
  CI (99.9%): [3.311, 4.422] (assumes normal distribution)


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
# Warmup Iteration   1: 4.250 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.252 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.006 ms/op
Iteration   1: 3.103 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.872 ms/op
                 createUser·p0.50:   3.068 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.227 ms/op
                 createUser·p0.999:  7.692 ms/op
                 createUser·p0.9999: 17.400 ms/op
                 createUser·p1.00:   17.727 ms/op

Iteration   2: 3.109 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.643 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.830 ms/op
                 createUser·p0.99:   4.350 ms/op
                 createUser·p0.999:  8.167 ms/op
                 createUser·p0.9999: 19.159 ms/op
                 createUser·p1.00:   19.464 ms/op

Iteration   3: 3.108 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.825 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.492 ms/op
                 createUser·p0.999:  10.151 ms/op
                 createUser·p0.9999: 20.447 ms/op
                 createUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309038
  mean =      3.107 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12888 
    [ 2.500,  5.000) = 294372 
    [ 5.000,  7.500) = 1345 
    [ 7.500, 10.000) = 197 
    [10.000, 12.500) = 21 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 95 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.643 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.789 ms/op
     p(99.0000) =      4.334 ms/op
     p(99.9000) =      8.380 ms/op
     p(99.9900) =     19.733 ms/op
     p(99.9990) =     20.513 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 4.141 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.005 ms/op
Iteration   1: 2.991 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.957 ms/op
                 existUser·p0.90:   3.469 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.473 ms/op
                 existUser·p0.999:  8.381 ms/op
                 existUser·p0.9999: 12.616 ms/op
                 existUser·p1.00:   12.829 ms/op

Iteration   2: 3.041 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.711 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.645 ms/op
                 existUser·p0.95:   3.805 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  6.996 ms/op
                 existUser·p0.9999: 13.720 ms/op
                 existUser·p1.00:   14.713 ms/op

Iteration   3: 3.094 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.860 ms/op
                 existUser·p0.50:   3.068 ms/op
                 existUser·p0.90:   3.686 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  8.520 ms/op
                 existUser·p0.9999: 17.334 ms/op
                 existUser·p1.00:   17.891 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 315604
  mean =      3.041 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1041 
    [ 1.250,  2.500) = 23804 
    [ 2.500,  3.750) = 272789 
    [ 3.750,  5.000) = 16558 
    [ 5.000,  6.250) = 580 
    [ 6.250,  7.500) = 419 
    [ 7.500,  8.750) = 166 
    [ 8.750, 10.000) = 87 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 47 
    [12.500, 13.750) = 40 
    [13.750, 15.000) = 12 
    [15.000, 16.250) = 20 
    [16.250, 17.500) = 35 
    [17.500, 18.750) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.711 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.596 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.020 ms/op
     p(99.9900) =     16.586 ms/op
     p(99.9990) =     17.783 ms/op
     p(99.9999) =     17.891 ms/op
    p(100.0000) =     17.891 ms/op


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
# Warmup Iteration   1: 4.299 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.265 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.146 ±(99.9%) 0.006 ms/op
Iteration   1: 3.120 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.729 ms/op
                 getUser·p0.50:   3.076 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.538 ms/op
                 getUser·p0.999:  8.511 ms/op
                 getUser·p0.9999: 13.222 ms/op
                 getUser·p1.00:   13.500 ms/op

Iteration   2: 3.141 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.749 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.030 ms/op
                 getUser·p0.999:  12.227 ms/op
                 getUser·p0.9999: 16.138 ms/op
                 getUser·p1.00:   16.400 ms/op

Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.751 ms/op
                 getUser·p0.50:   3.052 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.740 ms/op
                 getUser·p0.99:   4.252 ms/op
                 getUser·p0.999:  6.899 ms/op
                 getUser·p0.9999: 18.711 ms/op
                 getUser·p1.00:   20.513 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 308268
  mean =      3.115 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14326 
    [ 2.500,  5.000) = 291612 
    [ 5.000,  7.500) = 1786 
    [ 7.500, 10.000) = 207 
    [10.000, 12.500) = 138 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.666 ms/op
     p(95.0000) =      3.850 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =     10.568 ms/op
     p(99.9900) =     18.159 ms/op
     p(99.9990) =     20.271 ms/op
     p(99.9999) =     20.513 ms/op
    p(100.0000) =     20.513 ms/op


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
# Warmup Iteration   1: 5.640 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.069 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.933 ±(99.9%) 0.010 ms/op
Iteration   1: 3.848 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.577 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.350 ms/op
                 listUser·p0.95:   4.948 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  14.090 ms/op
                 listUser·p0.9999: 15.866 ms/op
                 listUser·p1.00:   16.269 ms/op

Iteration   2: 3.884 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.792 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.997 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.915 ms/op
                 listUser·p0.9999: 16.860 ms/op
                 listUser·p1.00:   17.203 ms/op

Iteration   3: 3.867 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.171 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.555 ms/op
                 listUser·p0.95:   5.695 ms/op
                 listUser·p0.99:   6.811 ms/op
                 listUser·p0.999:  15.520 ms/op
                 listUser·p0.9999: 22.335 ms/op
                 listUser·p1.00:   23.495 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 248180
  mean =      3.866 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2591 
    [ 2.500,  5.000) = 231465 
    [ 5.000,  7.500) = 12674 
    [ 7.500, 10.000) = 834 
    [10.000, 12.500) = 159 
    [12.500, 15.000) = 238 
    [15.000, 17.500) = 179 
    [17.500, 20.000) = 31 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 6 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.171 ms/op
     p(50.0000) =      3.777 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      5.186 ms/op
     p(99.0000) =      6.791 ms/op
     p(99.9000) =     14.792 ms/op
     p(99.9900) =     18.624 ms/op
     p(99.9990) =     22.972 ms/op
     p(99.9999) =     23.495 ms/op
    p(100.0000) =     23.495 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.303 ± 2.216  ops/ms
ClientGrpc.existUser                       thrpt       3  10.929 ± 4.898  ops/ms
ClientGrpc.getUser                         thrpt       3  10.408 ± 2.049  ops/ms
ClientGrpc.listUser                        thrpt       3   8.375 ± 6.302  ops/ms
ClientGrpc.createUser                       avgt       3   3.084 ± 0.656   ms/op
ClientGrpc.existUser                        avgt       3   2.976 ± 0.807   ms/op
ClientGrpc.getUser                          avgt       3   3.092 ± 0.643   ms/op
ClientGrpc.listUser                         avgt       3   3.866 ± 0.556   ms/op
ClientGrpc.createUser                     sample  309038   3.107 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.643           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.625           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.334           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.380           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.733           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.513           ms/op
ClientGrpc.existUser                      sample  315604   3.041 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.711           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.596           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.020           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.586           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.891           ms/op
ClientGrpc.getUser                        sample  308268   3.115 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.729           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.068           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.666           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.850           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.628           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.568           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.159           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.513           ms/op
ClientGrpc.listUser                       sample  248180   3.866 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.171           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.777           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.375           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.186           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.792           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.624           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.495           ms/op
