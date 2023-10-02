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
# Warmup Iteration   1: 4.323 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 9.944 ops/ms
Iteration   1: 10.027 ops/ms
Iteration   2: 10.177 ops/ms
Iteration   3: 10.295 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.166 ±(99.9%) 2.451 ops/ms [Average]
  (min, avg, max) = (10.027, 10.166, 10.295), stdev = 0.134
  CI (99.9%): [7.715, 12.618] (assumes normal distribution)


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
# Warmup Iteration   1: 7.774 ops/ms
# Warmup Iteration   2: 10.227 ops/ms
# Warmup Iteration   3: 10.522 ops/ms
Iteration   1: 10.858 ops/ms
Iteration   2: 10.564 ops/ms
Iteration   3: 10.836 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.753 ±(99.9%) 2.983 ops/ms [Average]
  (min, avg, max) = (10.564, 10.753, 10.858), stdev = 0.163
  CI (99.9%): [7.770, 13.735] (assumes normal distribution)


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
# Warmup Iteration   1: 7.399 ops/ms
# Warmup Iteration   2: 9.797 ops/ms
# Warmup Iteration   3: 10.063 ops/ms
Iteration   1: 10.262 ops/ms
Iteration   2: 10.144 ops/ms
Iteration   3: 10.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.268 ±(99.9%) 2.328 ops/ms [Average]
  (min, avg, max) = (10.144, 10.268, 10.399), stdev = 0.128
  CI (99.9%): [7.940, 12.596] (assumes normal distribution)


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
# Warmup Iteration   1: 5.556 ops/ms
# Warmup Iteration   2: 7.960 ops/ms
# Warmup Iteration   3: 8.074 ops/ms
Iteration   1: 8.140 ops/ms
Iteration   2: 8.198 ops/ms
Iteration   3: 8.062 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.133 ±(99.9%) 1.242 ops/ms [Average]
  (min, avg, max) = (8.062, 8.133, 8.198), stdev = 0.068
  CI (99.9%): [6.891, 9.375] (assumes normal distribution)


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
# Warmup Iteration   1: 4.191 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.217 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.185 ±(99.9%) 0.003 ms/op
Iteration   1: 3.168 ±(99.9%) 0.002 ms/op
Iteration   2: 3.139 ±(99.9%) 0.001 ms/op
Iteration   3: 3.129 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.145 ±(99.9%) 0.369 ms/op [Average]
  (min, avg, max) = (3.129, 3.145, 3.168), stdev = 0.020
  CI (99.9%): [2.776, 3.515] (assumes normal distribution)


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
# Warmup Iteration   1: 3.956 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.098 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.052 ±(99.9%) 0.003 ms/op
Iteration   1: 3.093 ±(99.9%) 0.001 ms/op
Iteration   2: 3.053 ±(99.9%) 0.001 ms/op
Iteration   3: 2.934 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.027 ±(99.9%) 1.508 ms/op [Average]
  (min, avg, max) = (2.934, 3.027, 3.093), stdev = 0.083
  CI (99.9%): [1.519, 4.535] (assumes normal distribution)


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
# Warmup Iteration   1: 3.656 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.177 ±(99.9%) 0.003 ms/op
Iteration   1: 3.129 ±(99.9%) 0.003 ms/op
Iteration   2: 3.135 ±(99.9%) 0.002 ms/op
Iteration   3: 3.126 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.130 ±(99.9%) 0.087 ms/op [Average]
  (min, avg, max) = (3.126, 3.130, 3.135), stdev = 0.005
  CI (99.9%): [3.043, 3.217] (assumes normal distribution)


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
# Warmup Iteration   1: 5.268 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.013 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 3.942 ±(99.9%) 0.026 ms/op
Iteration   1: 3.965 ±(99.9%) 0.036 ms/op
Iteration   2: 3.963 ±(99.9%) 0.014 ms/op
Iteration   3: 3.955 ±(99.9%) 0.039 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.961 ±(99.9%) 0.088 ms/op [Average]
  (min, avg, max) = (3.955, 3.961, 3.965), stdev = 0.005
  CI (99.9%): [3.873, 4.048] (assumes normal distribution)


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
# Warmup Iteration   1: 4.169 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.298 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.006 ms/op
Iteration   1: 3.182 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.775 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.846 ms/op
                 createUser·p0.95:   4.002 ms/op
                 createUser·p0.99:   4.424 ms/op
                 createUser·p0.999:  7.274 ms/op
                 createUser·p0.9999: 12.548 ms/op
                 createUser·p1.00:   13.009 ms/op

Iteration   2: 3.192 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.851 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.699 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.252 ms/op
                 createUser·p0.999:  8.347 ms/op
                 createUser·p0.9999: 13.287 ms/op
                 createUser·p1.00:   13.550 ms/op

Iteration   3: 3.182 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.599 ms/op
                 createUser·p0.50:   3.138 ms/op
                 createUser·p0.90:   3.715 ms/op
                 createUser·p0.95:   3.871 ms/op
                 createUser·p0.99:   4.423 ms/op
                 createUser·p0.999:  8.904 ms/op
                 createUser·p0.9999: 14.562 ms/op
                 createUser·p1.00:   15.352 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 301229
  mean =      3.185 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 831 
    [ 1.250,  2.500) = 5883 
    [ 2.500,  3.750) = 264666 
    [ 3.750,  5.000) = 28300 
    [ 5.000,  6.250) = 826 
    [ 6.250,  7.500) = 320 
    [ 7.500,  8.750) = 127 
    [ 8.750, 10.000) = 71 
    [10.000, 11.250) = 34 
    [11.250, 12.500) = 69 
    [12.500, 13.750) = 81 
    [13.750, 15.000) = 14 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.599 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.748 ms/op
     p(95.0000) =      3.903 ms/op
     p(99.0000) =      4.383 ms/op
     p(99.9000) =      8.552 ms/op
     p(99.9900) =     13.316 ms/op
     p(99.9990) =     15.237 ms/op
     p(99.9999) =     15.352 ms/op
    p(100.0000) =     15.352 ms/op


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
# Warmup Iteration   1: 3.913 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.005 ms/op
Iteration   1: 3.046 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.840 ms/op
                 existUser·p0.50:   3.015 ms/op
                 existUser·p0.90:   3.527 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.341 ms/op
                 existUser·p0.999:  6.922 ms/op
                 existUser·p0.9999: 11.903 ms/op
                 existUser·p1.00:   12.190 ms/op

Iteration   2: 3.041 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   3.027 ms/op
                 existUser·p0.90:   3.650 ms/op
                 existUser·p0.95:   3.854 ms/op
                 existUser·p0.99:   4.383 ms/op
                 existUser·p0.999:  5.865 ms/op
                 existUser·p0.9999: 12.222 ms/op
                 existUser·p1.00:   12.452 ms/op

Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.592 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.784 ms/op
                 existUser·p0.999:  11.665 ms/op
                 existUser·p0.9999: 14.707 ms/op
                 existUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313810
  mean =      3.057 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1042 
    [ 1.250,  2.500) = 15737 
    [ 2.500,  3.750) = 280948 
    [ 3.750,  5.000) = 14348 
    [ 5.000,  6.250) = 1045 
    [ 6.250,  7.500) = 363 
    [ 7.500,  8.750) = 59 
    [ 8.750, 10.000) = 56 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 123 
    [12.500, 13.750) = 18 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.716 ms/op
     p(50.0000) =      3.023 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.756 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      7.602 ms/op
     p(99.9900) =     13.881 ms/op
     p(99.9990) =     15.532 ms/op
     p(99.9999) =     15.794 ms/op
    p(100.0000) =     15.794 ms/op


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
# Warmup Iteration   1: 4.269 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.280 ±(99.9%) 0.006 ms/op
Iteration   1: 3.207 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.892 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.424 ms/op
                 getUser·p0.999:  8.552 ms/op
                 getUser·p0.9999: 11.387 ms/op
                 getUser·p1.00:   11.665 ms/op

Iteration   2: 3.154 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.753 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.699 ms/op
                 getUser·p0.95:   3.899 ms/op
                 getUser·p0.99:   4.645 ms/op
                 getUser·p0.999:  8.385 ms/op
                 getUser·p0.9999: 12.681 ms/op
                 getUser·p1.00:   13.058 ms/op

Iteration   3: 3.123 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.710 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.863 ms/op
                 getUser·p0.99:   4.383 ms/op
                 getUser·p0.999:  7.039 ms/op
                 getUser·p0.9999: 16.965 ms/op
                 getUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303679
  mean =      3.161 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 521 
    [ 1.250,  2.500) = 8209 
    [ 2.500,  3.750) = 268819 
    [ 3.750,  5.000) = 24402 
    [ 5.000,  6.250) = 1078 
    [ 6.250,  7.500) = 260 
    [ 7.500,  8.750) = 159 
    [ 8.750, 10.000) = 58 
    [10.000, 11.250) = 63 
    [11.250, 12.500) = 58 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 2 
    [15.000, 16.250) = 4 
    [16.250, 17.500) = 26 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.710 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.707 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.456 ms/op
     p(99.9000) =      8.162 ms/op
     p(99.9900) =     15.048 ms/op
     p(99.9990) =     17.201 ms/op
     p(99.9999) =     17.334 ms/op
    p(100.0000) =     17.334 ms/op


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
# Warmup Iteration   1: 4.022 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 4.143 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.927 ±(99.9%) 0.010 ms/op
Iteration   1: 3.941 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   0.986 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.903 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  15.497 ms/op
                 listUser·p0.9999: 19.263 ms/op
                 listUser·p1.00:   22.086 ms/op

Iteration   2: 3.956 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   0.802 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   6.668 ms/op
                 listUser·p0.999:  12.829 ms/op
                 listUser·p0.9999: 14.513 ms/op
                 listUser·p1.00:   15.401 ms/op

Iteration   3: 3.950 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.268 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.022 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.420 ms/op
                 listUser·p0.9999: 25.133 ms/op
                 listUser·p1.00:   27.001 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 243012
  mean =      3.949 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1387 
    [ 2.500,  5.000) = 230216 
    [ 5.000,  7.500) = 10288 
    [ 7.500, 10.000) = 620 
    [10.000, 12.500) = 142 
    [12.500, 15.000) = 213 
    [15.000, 17.500) = 80 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 17 

  Percentiles, ms/op:
      p(0.0000) =      0.802 ms/op
     p(50.0000) =      3.871 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      6.693 ms/op
     p(99.9000) =     13.418 ms/op
     p(99.9900) =     24.566 ms/op
     p(99.9990) =     25.199 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.166 ± 2.451  ops/ms
ClientGrpc.existUser                       thrpt       3  10.753 ± 2.983  ops/ms
ClientGrpc.getUser                         thrpt       3  10.268 ± 2.328  ops/ms
ClientGrpc.listUser                        thrpt       3   8.133 ± 1.242  ops/ms
ClientGrpc.createUser                       avgt       3   3.145 ± 0.369   ms/op
ClientGrpc.existUser                        avgt       3   3.027 ± 1.508   ms/op
ClientGrpc.getUser                          avgt       3   3.130 ± 0.087   ms/op
ClientGrpc.listUser                         avgt       3   3.961 ± 0.088   ms/op
ClientGrpc.createUser                     sample  301229   3.185 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.599           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.150           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.748           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.903           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.383           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.552           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          13.316           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.352           ms/op
ClientGrpc.existUser                      sample  313810   3.057 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.716           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.023           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.588           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.756           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.415           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.602           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          13.881           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          15.794           ms/op
ClientGrpc.getUser                        sample  303679   3.161 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.710           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.121           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.707           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.456           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.162           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          15.048           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.334           ms/op
ClientGrpc.listUser                       sample  243012   3.949 ± 0.005   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.802           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.871           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.358           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           4.923           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.693           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.418           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.566           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.001           ms/op
