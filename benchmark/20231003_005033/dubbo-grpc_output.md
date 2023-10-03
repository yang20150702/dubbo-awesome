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
# Warmup Iteration   1: 4.020 ops/ms
# Warmup Iteration   2: 8.670 ops/ms
# Warmup Iteration   3: 9.766 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.269 ops/ms
Iteration   3: 10.194 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.223 ±(99.9%) 0.728 ops/ms [Average]
  (min, avg, max) = (10.194, 10.223, 10.269), stdev = 0.040
  CI (99.9%): [9.496, 10.951] (assumes normal distribution)


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
# Warmup Iteration   1: 7.351 ops/ms
# Warmup Iteration   2: 10.222 ops/ms
# Warmup Iteration   3: 10.436 ops/ms
Iteration   1: 10.901 ops/ms
Iteration   2: 10.927 ops/ms
Iteration   3: 10.812 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.880 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (10.812, 10.880, 10.927), stdev = 0.060
  CI (99.9%): [9.777, 11.984] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.999 ops/ms
# Warmup Iteration   2: 9.794 ops/ms
# Warmup Iteration   3: 10.229 ops/ms
Iteration   1: 10.340 ops/ms
Iteration   2: 10.220 ops/ms
Iteration   3: 10.336 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.299 ±(99.9%) 1.234 ops/ms [Average]
  (min, avg, max) = (10.220, 10.299, 10.340), stdev = 0.068
  CI (99.9%): [9.064, 11.533] (assumes normal distribution)


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
# Warmup Iteration   1: 5.250 ops/ms
# Warmup Iteration   2: 7.837 ops/ms
# Warmup Iteration   3: 8.044 ops/ms
Iteration   1: 8.136 ops/ms
Iteration   2: 8.222 ops/ms
Iteration   3: 8.197 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.185 ±(99.9%) 0.811 ops/ms [Average]
  (min, avg, max) = (8.136, 8.185, 8.222), stdev = 0.044
  CI (99.9%): [7.374, 8.996] (assumes normal distribution)


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
# Warmup Iteration   1: 4.383 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.350 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.187 ±(99.9%) 0.001 ms/op
Iteration   1: 3.150 ±(99.9%) 0.002 ms/op
Iteration   2: 3.139 ±(99.9%) 0.002 ms/op
Iteration   3: 3.232 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.174 ±(99.9%) 0.925 ms/op [Average]
  (min, avg, max) = (3.139, 3.174, 3.232), stdev = 0.051
  CI (99.9%): [2.249, 4.099] (assumes normal distribution)


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
# Warmup Iteration   1: 3.944 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.140 ±(99.9%) 0.002 ms/op
Iteration   1: 3.057 ±(99.9%) 0.002 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 3.023 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.005 ±(99.9%) 1.143 ms/op [Average]
  (min, avg, max) = (2.935, 3.005, 3.057), stdev = 0.063
  CI (99.9%): [1.862, 4.149] (assumes normal distribution)


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
# Warmup Iteration   1: 4.411 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.230 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.002 ms/op
Iteration   1: 3.163 ±(99.9%) 0.003 ms/op
Iteration   2: 3.157 ±(99.9%) 0.003 ms/op
Iteration   3: 3.109 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.143 ±(99.9%) 0.545 ms/op [Average]
  (min, avg, max) = (3.109, 3.143, 3.163), stdev = 0.030
  CI (99.9%): [2.598, 3.688] (assumes normal distribution)


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
# Warmup Iteration   1: 5.007 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.024 ms/op
Iteration   1: 3.905 ±(99.9%) 0.008 ms/op
Iteration   2: 3.986 ±(99.9%) 0.019 ms/op
Iteration   3: 3.914 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.935 ±(99.9%) 0.810 ms/op [Average]
  (min, avg, max) = (3.905, 3.935, 3.986), stdev = 0.044
  CI (99.9%): [3.125, 4.745] (assumes normal distribution)


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
# Warmup Iteration   1: 4.264 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.310 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.251 ±(99.9%) 0.007 ms/op
Iteration   1: 3.168 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.873 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.805 ms/op
                 createUser·p0.95:   3.994 ms/op
                 createUser·p0.99:   4.620 ms/op
                 createUser·p0.999:  10.869 ms/op
                 createUser·p0.9999: 12.921 ms/op
                 createUser·p1.00:   13.418 ms/op

Iteration   2: 3.134 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.975 ms/op
                 createUser·p0.50:   3.080 ms/op
                 createUser·p0.90:   3.690 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.293 ms/op
                 createUser·p0.999:  7.192 ms/op
                 createUser·p0.9999: 14.001 ms/op
                 createUser·p1.00:   14.205 ms/op

Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.688 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.895 ms/op
                 createUser·p0.99:   4.473 ms/op
                 createUser·p0.999:  8.597 ms/op
                 createUser·p0.9999: 16.799 ms/op
                 createUser·p1.00:   17.072 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305693
  mean =      3.142 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 266 
    [ 1.250,  2.500) = 8618 
    [ 2.500,  3.750) = 268789 
    [ 3.750,  5.000) = 26326 
    [ 5.000,  6.250) = 905 
    [ 6.250,  7.500) = 380 
    [ 7.500,  8.750) = 115 
    [ 8.750, 10.000) = 3 
    [10.000, 11.250) = 38 
    [11.250, 12.500) = 56 
    [12.500, 13.750) = 77 
    [13.750, 15.000) = 97 
    [15.000, 16.250) = 9 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.688 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.715 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.361 ms/op
     p(99.9900) =     14.753 ms/op
     p(99.9990) =     16.974 ms/op
     p(99.9999) =     17.072 ms/op
    p(100.0000) =     17.072 ms/op


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
# Warmup Iteration   1: 4.285 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.974 ±(99.9%) 0.005 ms/op
Iteration   1: 2.982 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.815 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.479 ms/op
                 existUser·p0.95:   3.682 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  7.858 ms/op
                 existUser·p0.9999: 14.017 ms/op
                 existUser·p1.00:   14.418 ms/op

Iteration   2: 3.077 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.501 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.621 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.350 ms/op
                 existUser·p0.999:  8.167 ms/op
                 existUser·p0.9999: 14.749 ms/op
                 existUser·p1.00:   15.188 ms/op

Iteration   3: 2.977 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.610 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.490 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.059 ms/op
                 existUser·p0.999:  6.497 ms/op
                 existUser·p0.9999: 18.121 ms/op
                 existUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318782
  mean =      3.011 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 617 
    [ 1.250,  2.500) = 21498 
    [ 2.500,  3.750) = 281617 
    [ 3.750,  5.000) = 13772 
    [ 5.000,  6.250) = 523 
    [ 6.250,  7.500) = 422 
    [ 7.500,  8.750) = 96 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 65 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 51 
    [13.750, 15.000) = 54 
    [15.000, 16.250) = 2 
    [16.250, 17.500) = 18 
    [17.500, 18.750) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.501 ms/op
     p(50.0000) =      2.974 ms/op
     p(90.0000) =      3.531 ms/op
     p(95.0000) =      3.736 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.596 ms/op
     p(99.9900) =     16.339 ms/op
     p(99.9990) =     18.317 ms/op
     p(99.9999) =     18.350 ms/op
    p(100.0000) =     18.350 ms/op


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
# Warmup Iteration   1: 4.304 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.274 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.163 ±(99.9%) 0.007 ms/op
Iteration   1: 3.040 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.730 ms/op
                 getUser·p0.50:   3.002 ms/op
                 getUser·p0.90:   3.490 ms/op
                 getUser·p0.95:   3.817 ms/op
                 getUser·p0.99:   4.637 ms/op
                 getUser·p0.999:  6.953 ms/op
                 getUser·p0.9999: 19.140 ms/op
                 getUser·p1.00:   20.349 ms/op

Iteration   2: 3.100 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.818 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.867 ms/op
                 getUser·p0.99:   4.309 ms/op
                 getUser·p0.999:  6.455 ms/op
                 getUser·p0.9999: 20.764 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.814 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.572 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.312 ms/op
                 getUser·p0.999:  7.581 ms/op
                 getUser·p0.9999: 22.502 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311316
  mean =      3.084 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10505 
    [ 2.500,  5.000) = 299152 
    [ 5.000,  7.500) = 1413 
    [ 7.500, 10.000) = 75 
    [10.000, 12.500) = 11 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 68 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.730 ms/op
     p(50.0000) =      3.039 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.822 ms/op
     p(99.0000) =      4.399 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     22.053 ms/op
     p(99.9990) =     22.672 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


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
# Warmup Iteration   1: 4.755 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.236 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.908 ±(99.9%) 0.009 ms/op
Iteration   1: 4.002 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.019 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.792 ms/op
                 listUser·p0.95:   5.759 ms/op
                 listUser·p0.99:   6.775 ms/op
                 listUser·p0.999:  12.678 ms/op
                 listUser·p0.9999: 14.467 ms/op
                 listUser·p1.00:   15.598 ms/op

Iteration   2: 3.896 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.977 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   5.317 ms/op
                 listUser·p0.99:   6.644 ms/op
                 listUser·p0.999:  14.106 ms/op
                 listUser·p0.9999: 16.868 ms/op
                 listUser·p1.00:   17.924 ms/op

Iteration   3: 3.951 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.260 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.440 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  13.520 ms/op
                 listUser·p0.9999: 20.229 ms/op
                 listUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243345
  mean =      3.950 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2925 
    [ 2.500,  5.000) = 223555 
    [ 5.000,  7.500) = 15827 
    [ 7.500, 10.000) = 560 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.977 ms/op
     p(50.0000) =      3.842 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      6.668 ms/op
     p(99.9000) =     13.200 ms/op
     p(99.9900) =     18.437 ms/op
     p(99.9990) =     20.503 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.223 ± 0.728  ops/ms
ClientGrpc.existUser                       thrpt       3  10.880 ± 1.104  ops/ms
ClientGrpc.getUser                         thrpt       3  10.299 ± 1.234  ops/ms
ClientGrpc.listUser                        thrpt       3   8.185 ± 0.811  ops/ms
ClientGrpc.createUser                       avgt       3   3.174 ± 0.925   ms/op
ClientGrpc.existUser                        avgt       3   3.005 ± 1.143   ms/op
ClientGrpc.getUser                          avgt       3   3.143 ± 0.545   ms/op
ClientGrpc.listUser                         avgt       3   3.935 ± 0.810   ms/op
ClientGrpc.createUser                     sample  305693   3.142 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.688           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.715           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.940           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.456           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.361           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.753           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          17.072           ms/op
ClientGrpc.existUser                      sample  318782   3.011 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.501           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.974           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.531           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.736           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.596           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.339           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.350           ms/op
ClientGrpc.getUser                        sample  311316   3.084 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.730           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.039           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.822           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.399           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.914           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.053           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  243345   3.950 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.977           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.842           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.555           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.407           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.668           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.200           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.437           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.546           ms/op
