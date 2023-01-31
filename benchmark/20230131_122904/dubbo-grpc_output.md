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
# Warmup Iteration   1: 4.143 ops/ms
# Warmup Iteration   2: 8.793 ops/ms
# Warmup Iteration   3: 9.828 ops/ms
Iteration   1: 10.123 ops/ms
Iteration   2: 9.892 ops/ms
Iteration   3: 10.132 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.049 ±(99.9%) 2.484 ops/ms [Average]
  (min, avg, max) = (9.892, 10.049, 10.132), stdev = 0.136
  CI (99.9%): [7.565, 12.533] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.822 ops/ms
# Warmup Iteration   2: 10.039 ops/ms
# Warmup Iteration   3: 10.925 ops/ms
Iteration   1: 11.311 ops/ms
Iteration   2: 10.578 ops/ms
Iteration   3: 10.341 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.743 ±(99.9%) 9.225 ops/ms [Average]
  (min, avg, max) = (10.341, 10.743, 11.311), stdev = 0.506
  CI (99.9%): [1.518, 19.967] (assumes normal distribution)


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
# Warmup Iteration   1: 6.975 ops/ms
# Warmup Iteration   2: 9.830 ops/ms
# Warmup Iteration   3: 9.839 ops/ms
Iteration   1: 9.989 ops/ms
Iteration   2: 9.986 ops/ms
Iteration   3: 9.976 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.984 ±(99.9%) 0.126 ops/ms [Average]
  (min, avg, max) = (9.976, 9.984, 9.989), stdev = 0.007
  CI (99.9%): [9.857, 10.110] (assumes normal distribution)


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
# Warmup Iteration   1: 5.401 ops/ms
# Warmup Iteration   2: 7.817 ops/ms
# Warmup Iteration   3: 7.797 ops/ms
Iteration   1: 7.844 ops/ms
Iteration   2: 8.049 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.928 ±(99.9%) 1.964 ops/ms [Average]
  (min, avg, max) = (7.844, 7.928, 8.049), stdev = 0.108
  CI (99.9%): [5.963, 9.892] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.244 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.288 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.168 ±(99.9%) 0.003 ms/op
Iteration   1: 3.098 ±(99.9%) 0.002 ms/op
Iteration   2: 3.219 ±(99.9%) 0.001 ms/op
Iteration   3: 3.150 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.156 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.098, 3.156, 3.219), stdev = 0.061
  CI (99.9%): [2.050, 4.262] (assumes normal distribution)


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
# Warmup Iteration   1: 3.978 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.078 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.101 ±(99.9%) 0.003 ms/op
Iteration   1: 3.078 ±(99.9%) 0.002 ms/op
Iteration   2: 3.080 ±(99.9%) 0.002 ms/op
Iteration   3: 2.929 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.029 ±(99.9%) 1.582 ms/op [Average]
  (min, avg, max) = (2.929, 3.029, 3.080), stdev = 0.087
  CI (99.9%): [1.447, 4.611] (assumes normal distribution)


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
# Warmup Iteration   1: 4.104 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.002 ms/op
Iteration   1: 3.198 ±(99.9%) 0.002 ms/op
Iteration   2: 3.176 ±(99.9%) 0.003 ms/op
Iteration   3: 3.191 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.188 ±(99.9%) 0.207 ms/op [Average]
  (min, avg, max) = (3.176, 3.188, 3.198), stdev = 0.011
  CI (99.9%): [2.981, 3.395] (assumes normal distribution)


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
# Warmup Iteration   1: 4.784 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.991 ±(99.9%) 0.028 ms/op
Iteration   1: 3.915 ±(99.9%) 0.040 ms/op
Iteration   2: 4.091 ±(99.9%) 0.021 ms/op
Iteration   3: 4.038 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.015 ±(99.9%) 1.646 ms/op [Average]
  (min, avg, max) = (3.915, 4.015, 4.091), stdev = 0.090
  CI (99.9%): [2.369, 5.660] (assumes normal distribution)


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
# Warmup Iteration   1: 4.399 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.214 ±(99.9%) 0.006 ms/op
Iteration   1: 3.151 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.880 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.022 ms/op
                 createUser·p0.99:   4.391 ms/op
                 createUser·p0.999:  6.291 ms/op
                 createUser·p0.9999: 12.534 ms/op
                 createUser·p1.00:   12.780 ms/op

Iteration   2: 3.110 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.772 ms/op
                 createUser·p0.50:   3.121 ms/op
                 createUser·p0.90:   3.768 ms/op
                 createUser·p0.95:   3.973 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  8.916 ms/op
                 createUser·p0.9999: 13.430 ms/op
                 createUser·p1.00:   13.615 ms/op

Iteration   3: 3.160 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.670 ms/op
                 createUser·p0.50:   3.142 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.026 ms/op
                 createUser·p0.99:   4.334 ms/op
                 createUser·p0.999:  7.294 ms/op
                 createUser·p0.9999: 22.008 ms/op
                 createUser·p1.00:   22.643 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305497
  mean =      3.140 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25372 
    [ 2.500,  5.000) = 279012 
    [ 5.000,  7.500) = 780 
    [ 7.500, 10.000) = 130 
    [10.000, 12.500) = 39 
    [12.500, 15.000) = 96 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.670 ms/op
     p(50.0000) =      3.125 ms/op
     p(90.0000) =      3.801 ms/op
     p(95.0000) =      4.010 ms/op
     p(99.0000) =      4.375 ms/op
     p(99.9000) =      7.795 ms/op
     p(99.9900) =     20.673 ms/op
     p(99.9990) =     22.539 ms/op
     p(99.9999) =     22.643 ms/op
    p(100.0000) =     22.643 ms/op


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
# Warmup Iteration   1: 4.055 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.093 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.027 ±(99.9%) 0.006 ms/op
Iteration   1: 3.116 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.926 ms/op
                 existUser·p0.50:   3.080 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   4.415 ms/op
                 existUser·p0.999:  7.928 ms/op
                 existUser·p0.9999: 14.028 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   2: 3.033 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.788 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.323 ms/op
                 existUser·p0.9999: 13.746 ms/op
                 existUser·p1.00:   14.221 ms/op

Iteration   3: 3.109 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.784 ms/op
                 existUser·p0.50:   3.117 ms/op
                 existUser·p0.90:   3.797 ms/op
                 existUser·p0.95:   3.949 ms/op
                 existUser·p0.99:   4.202 ms/op
                 existUser·p0.999:  6.365 ms/op
                 existUser·p0.9999: 16.506 ms/op
                 existUser·p1.00:   17.236 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 311174
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1326 
    [ 1.250,  2.500) = 30944 
    [ 2.500,  3.750) = 246405 
    [ 3.750,  5.000) = 31524 
    [ 5.000,  6.250) = 472 
    [ 6.250,  7.500) = 258 
    [ 7.500,  8.750) = 112 
    [ 8.750, 10.000) = 4 
    [10.000, 11.250) = 1 
    [11.250, 12.500) = 0 
    [12.500, 13.750) = 68 
    [13.750, 15.000) = 49 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 11 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.784 ms/op
     p(50.0000) =      3.068 ms/op
     p(90.0000) =      3.760 ms/op
     p(95.0000) =      3.932 ms/op
     p(99.0000) =      4.260 ms/op
     p(99.9000) =      7.067 ms/op
     p(99.9900) =     14.187 ms/op
     p(99.9990) =     17.098 ms/op
     p(99.9999) =     17.236 ms/op
    p(100.0000) =     17.236 ms/op


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
# Warmup Iteration   1: 4.190 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.188 ±(99.9%) 0.007 ms/op
Iteration   1: 3.162 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.568 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.789 ms/op
                 getUser·p0.95:   3.990 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  7.296 ms/op
                 getUser·p0.9999: 16.085 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   2: 3.163 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   3.133 ms/op
                 getUser·p0.90:   3.781 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.317 ms/op
                 getUser·p0.999:  7.050 ms/op
                 getUser·p0.9999: 17.269 ms/op
                 getUser·p1.00:   19.038 ms/op

Iteration   3: 3.226 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.808 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.936 ms/op
                 getUser·p0.95:   4.104 ms/op
                 getUser·p0.99:   4.440 ms/op
                 getUser·p0.999:  9.172 ms/op
                 getUser·p0.9999: 19.958 ms/op
                 getUser·p1.00:   20.382 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 301517
  mean =      3.183 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18581 
    [ 2.500,  5.000) = 281906 
    [ 5.000,  7.500) = 736 
    [ 7.500, 10.000) = 98 
    [10.000, 12.500) = 19 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 59 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.568 ms/op
     p(50.0000) =      3.154 ms/op
     p(90.0000) =      3.838 ms/op
     p(95.0000) =      4.014 ms/op
     p(99.0000) =      4.391 ms/op
     p(99.9000) =      7.434 ms/op
     p(99.9900) =     18.317 ms/op
     p(99.9990) =     20.283 ms/op
     p(99.9999) =     20.382 ms/op
    p(100.0000) =     20.382 ms/op


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
# Warmup Iteration   1: 5.307 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.210 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.022 ±(99.9%) 0.011 ms/op
Iteration   1: 4.066 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.881 ms/op
                 listUser·p0.999:  12.816 ms/op
                 listUser·p0.9999: 21.149 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   2: 4.011 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.626 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   7.029 ms/op
                 listUser·p0.999:  14.606 ms/op
                 listUser·p0.9999: 17.171 ms/op
                 listUser·p1.00:   18.743 ms/op

Iteration   3: 4.150 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.237 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.209 ms/op
                 listUser·p0.999:  15.794 ms/op
                 listUser·p0.9999: 20.382 ms/op
                 listUser·p1.00:   20.709 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235602
  mean =      4.075 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2206 
    [ 2.500,  5.000) = 197991 
    [ 5.000,  7.500) = 33874 
    [ 7.500, 10.000) = 1106 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 122 
    [15.000, 17.500) = 146 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.626 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.734 ms/op
     p(99.0000) =      7.029 ms/op
     p(99.9000) =     14.647 ms/op
     p(99.9900) =     20.494 ms/op
     p(99.9990) =     21.898 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.049 ± 2.484  ops/ms
ClientGrpc.existUser                       thrpt       3  10.743 ± 9.225  ops/ms
ClientGrpc.getUser                         thrpt       3   9.984 ± 0.126  ops/ms
ClientGrpc.listUser                        thrpt       3   7.928 ± 1.964  ops/ms
ClientGrpc.createUser                       avgt       3   3.156 ± 1.106   ms/op
ClientGrpc.existUser                        avgt       3   3.029 ± 1.582   ms/op
ClientGrpc.getUser                          avgt       3   3.188 ± 0.207   ms/op
ClientGrpc.listUser                         avgt       3   4.015 ± 1.646   ms/op
ClientGrpc.createUser                     sample  305497   3.140 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.670           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.125           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.801           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.010           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.795           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.673           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          22.643           ms/op
ClientGrpc.existUser                      sample  311174   3.085 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.784           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.068           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.760           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.932           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.260           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.067           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.187           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.236           ms/op
ClientGrpc.getUser                        sample  301517   3.183 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.568           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.154           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.838           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.014           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.391           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.434           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.317           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.382           ms/op
ClientGrpc.listUser                       sample  235602   4.075 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.626           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.734           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.029           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.647           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.494           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          21.987           ms/op
