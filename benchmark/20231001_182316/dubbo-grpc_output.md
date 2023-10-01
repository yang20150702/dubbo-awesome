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
# Warmup Iteration   1: 3.541 ops/ms
# Warmup Iteration   2: 8.396 ops/ms
# Warmup Iteration   3: 9.412 ops/ms
Iteration   1: 9.907 ops/ms
Iteration   2: 10.130 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  9.982 ±(99.9%) 2.346 ops/ms [Average]
  (min, avg, max) = (9.907, 9.982, 10.130), stdev = 0.129
  CI (99.9%): [7.636, 12.328] (assumes normal distribution)


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
# Warmup Iteration   1: 6.409 ops/ms
# Warmup Iteration   2: 10.009 ops/ms
# Warmup Iteration   3: 10.402 ops/ms
Iteration   1: 10.252 ops/ms
Iteration   2: 10.781 ops/ms
Iteration   3: 10.688 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.574 ±(99.9%) 5.159 ops/ms [Average]
  (min, avg, max) = (10.252, 10.574, 10.781), stdev = 0.283
  CI (99.9%): [5.415, 15.733] (assumes normal distribution)


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
# Warmup Iteration   1: 6.437 ops/ms
# Warmup Iteration   2: 9.671 ops/ms
# Warmup Iteration   3: 9.810 ops/ms
Iteration   1: 10.038 ops/ms
Iteration   2: 9.907 ops/ms
Iteration   3: 10.025 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.990 ±(99.9%) 1.313 ops/ms [Average]
  (min, avg, max) = (9.907, 9.990, 10.038), stdev = 0.072
  CI (99.9%): [8.677, 11.303] (assumes normal distribution)


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
# Warmup Iteration   1: 5.121 ops/ms
# Warmup Iteration   2: 7.552 ops/ms
# Warmup Iteration   3: 8.109 ops/ms
Iteration   1: 7.975 ops/ms
Iteration   2: 7.934 ops/ms
Iteration   3: 7.916 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.942 ±(99.9%) 0.557 ops/ms [Average]
  (min, avg, max) = (7.916, 7.942, 7.975), stdev = 0.031
  CI (99.9%): [7.385, 8.499] (assumes normal distribution)


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
# Warmup Iteration   1: 4.582 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 3.371 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.283 ±(99.9%) 0.003 ms/op
Iteration   1: 3.209 ±(99.9%) 0.002 ms/op
Iteration   2: 3.210 ±(99.9%) 0.001 ms/op
Iteration   3: 3.243 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.221 ±(99.9%) 0.355 ms/op [Average]
  (min, avg, max) = (3.209, 3.221, 3.243), stdev = 0.019
  CI (99.9%): [2.866, 3.576] (assumes normal distribution)


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
# Warmup Iteration   1: 4.390 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.002 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.026 ±(99.9%) 0.005 ms/op
Iteration   3: 3.051 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.067 ±(99.9%) 0.913 ms/op [Average]
  (min, avg, max) = (3.026, 3.067, 3.122), stdev = 0.050
  CI (99.9%): [2.154, 3.979] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 3.337 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.006 ms/op
Iteration   1: 3.224 ±(99.9%) 0.002 ms/op
Iteration   2: 3.216 ±(99.9%) 0.002 ms/op
Iteration   3: 3.131 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.190 ±(99.9%) 0.937 ms/op [Average]
  (min, avg, max) = (3.131, 3.190, 3.224), stdev = 0.051
  CI (99.9%): [2.253, 4.127] (assumes normal distribution)


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
# Warmup Iteration   1: 5.907 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.188 ±(99.9%) 0.038 ms/op
# Warmup Iteration   3: 4.008 ±(99.9%) 0.031 ms/op
Iteration   1: 4.051 ±(99.9%) 0.048 ms/op
Iteration   2: 4.024 ±(99.9%) 0.019 ms/op
Iteration   3: 4.012 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.029 ±(99.9%) 0.371 ms/op [Average]
  (min, avg, max) = (4.012, 4.029, 4.051), stdev = 0.020
  CI (99.9%): [3.658, 4.400] (assumes normal distribution)


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
# Warmup Iteration   1: 4.510 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.403 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.231 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.706 ms/op
                 createUser·p0.50:   3.183 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.661 ms/op
                 createUser·p0.999:  8.832 ms/op
                 createUser·p0.9999: 20.939 ms/op
                 createUser·p1.00:   21.037 ms/op

Iteration   2: 3.171 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.926 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.842 ms/op
                 createUser·p0.99:   4.579 ms/op
                 createUser·p0.999:  8.487 ms/op
                 createUser·p0.9999: 23.351 ms/op
                 createUser·p1.00:   23.822 ms/op

Iteration   3: 3.169 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.921 ms/op
                 createUser·p0.50:   3.117 ms/op
                 createUser·p0.90:   3.686 ms/op
                 createUser·p0.95:   3.932 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  10.224 ms/op
                 createUser·p0.9999: 24.540 ms/op
                 createUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 300824
  mean =      3.190 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7718 
    [ 2.500,  5.000) = 290639 
    [ 5.000,  7.500) = 1748 
    [ 7.500, 10.000) = 447 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 6 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 69 
    [22.500, 25.000) = 84 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.706 ms/op
     p(50.0000) =      3.133 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.912 ms/op
     p(99.0000) =      4.758 ms/op
     p(99.9000) =      9.164 ms/op
     p(99.9900) =     23.552 ms/op
     p(99.9990) =     24.707 ms/op
     p(99.9999) =     24.740 ms/op
    p(100.0000) =     24.740 ms/op


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
# Warmup Iteration   1: 4.215 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.112 ±(99.9%) 0.006 ms/op
Iteration   1: 3.026 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.731 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.457 ms/op
                 existUser·p0.95:   3.670 ms/op
                 existUser·p0.99:   4.506 ms/op
                 existUser·p0.999:  10.207 ms/op
                 existUser·p0.9999: 13.646 ms/op
                 existUser·p1.00:   15.679 ms/op

Iteration   2: 3.051 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.948 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.744 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  7.599 ms/op
                 existUser·p0.9999: 13.444 ms/op
                 existUser·p1.00:   13.877 ms/op

Iteration   3: 3.109 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.496 ms/op
                 existUser·p0.50:   3.043 ms/op
                 existUser·p0.90:   3.625 ms/op
                 existUser·p0.95:   3.863 ms/op
                 existUser·p0.99:   5.079 ms/op
                 existUser·p0.999:  7.843 ms/op
                 existUser·p0.9999: 18.243 ms/op
                 existUser·p1.00:   18.776 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313289
  mean =      3.061 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 502 
    [ 1.250,  2.500) = 13730 
    [ 2.500,  3.750) = 282687 
    [ 3.750,  5.000) = 13972 
    [ 5.000,  6.250) = 1143 
    [ 6.250,  7.500) = 753 
    [ 7.500,  8.750) = 209 
    [ 8.750, 10.000) = 64 
    [10.000, 11.250) = 46 
    [11.250, 12.500) = 22 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 6 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 33 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.496 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.539 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.694 ms/op
     p(99.9000) =      8.499 ms/op
     p(99.9900) =     17.620 ms/op
     p(99.9990) =     18.702 ms/op
     p(99.9999) =     18.776 ms/op
    p(100.0000) =     18.776 ms/op


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
# Warmup Iteration   1: 4.651 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 3.326 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.243 ±(99.9%) 0.007 ms/op
Iteration   1: 3.182 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.695 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   5.108 ms/op
                 getUser·p0.999:  8.151 ms/op
                 getUser·p0.9999: 20.247 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   2: 3.167 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.800 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   4.882 ms/op
                 getUser·p0.999:  8.962 ms/op
                 getUser·p0.9999: 15.951 ms/op
                 getUser·p1.00:   16.450 ms/op

Iteration   3: 3.176 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.821 ms/op
                 getUser·p0.50:   3.113 ms/op
                 getUser·p0.90:   3.618 ms/op
                 getUser·p0.95:   3.891 ms/op
                 getUser·p0.99:   5.161 ms/op
                 getUser·p0.999:  13.970 ms/op
                 getUser·p0.9999: 18.940 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 302228
  mean =      3.175 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10287 
    [ 2.500,  5.000) = 288747 
    [ 5.000,  7.500) = 2475 
    [ 7.500, 10.000) = 402 
    [10.000, 12.500) = 49 
    [12.500, 15.000) = 108 
    [15.000, 17.500) = 94 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.670 ms/op
     p(95.0000) =      3.949 ms/op
     p(99.0000) =      5.054 ms/op
     p(99.9000) =     11.417 ms/op
     p(99.9900) =     19.719 ms/op
     p(99.9990) =     20.675 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


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
# Warmup Iteration   1: 5.759 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.346 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.107 ±(99.9%) 0.012 ms/op
Iteration   1: 4.159 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.548 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   6.136 ms/op
                 listUser·p0.99:   8.151 ms/op
                 listUser·p0.999:  16.355 ms/op
                 listUser·p0.9999: 18.628 ms/op
                 listUser·p1.00:   20.054 ms/op

Iteration   2: 4.132 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   3.961 ms/op
                 listUser·p0.90:   5.030 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   7.447 ms/op
                 listUser·p0.999:  16.056 ms/op
                 listUser·p0.9999: 27.476 ms/op
                 listUser·p1.00:   28.017 ms/op

Iteration   3: 4.087 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.890 ms/op
                 listUser·p0.50:   3.916 ms/op
                 listUser·p0.90:   4.932 ms/op
                 listUser·p0.95:   5.939 ms/op
                 listUser·p0.99:   7.422 ms/op
                 listUser·p0.999:  19.202 ms/op
                 listUser·p0.9999: 24.412 ms/op
                 listUser·p1.00:   25.133 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 232797
  mean =      4.126 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1544 
    [ 2.500,  5.000) = 206007 
    [ 5.000,  7.500) = 22508 
    [ 7.500, 10.000) = 2041 
    [10.000, 12.500) = 279 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 178 
    [17.500, 20.000) = 71 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.890 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.095 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.692 ms/op
     p(99.9000) =     16.715 ms/op
     p(99.9900) =     25.559 ms/op
     p(99.9990) =     27.973 ms/op
     p(99.9999) =     28.017 ms/op
    p(100.0000) =     28.017 ms/op


# Run complete. Total time: 00:13:07

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   9.982 ± 2.346  ops/ms
ClientGrpc.existUser                       thrpt       3  10.574 ± 5.159  ops/ms
ClientGrpc.getUser                         thrpt       3   9.990 ± 1.313  ops/ms
ClientGrpc.listUser                        thrpt       3   7.942 ± 0.557  ops/ms
ClientGrpc.createUser                       avgt       3   3.221 ± 0.355   ms/op
ClientGrpc.existUser                        avgt       3   3.067 ± 0.913   ms/op
ClientGrpc.getUser                          avgt       3   3.190 ± 0.937   ms/op
ClientGrpc.listUser                         avgt       3   4.029 ± 0.371   ms/op
ClientGrpc.createUser                     sample  300824   3.190 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.706           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.133           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.912           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.758           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.164           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.552           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          24.740           ms/op
ClientGrpc.existUser                      sample  313289   3.061 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.496           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.006           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.539           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.764           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.694           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.499           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.620           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.776           ms/op
ClientGrpc.getUser                        sample  302228   3.175 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.800           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.670           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.949           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.054           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.417           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.719           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.429           ms/op
ClientGrpc.listUser                       sample  232797   4.126 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.890           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.095           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.931           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.692           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.715           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          25.559           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.017           ms/op
