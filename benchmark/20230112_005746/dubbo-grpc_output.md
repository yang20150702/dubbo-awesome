# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.397 ops/ms
# Warmup Iteration   2: 9.132 ops/ms
# Warmup Iteration   3: 9.972 ops/ms
Iteration   1: 10.302 ops/ms
Iteration   2: 10.278 ops/ms
Iteration   3: 9.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.173 ±(99.9%) 3.717 ops/ms [Average]
  (min, avg, max) = (9.938, 10.173, 10.302), stdev = 0.204
  CI (99.9%): [6.456, 13.890] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 7.156 ops/ms
# Warmup Iteration   2: 10.236 ops/ms
# Warmup Iteration   3: 10.249 ops/ms
Iteration   1: 10.280 ops/ms
Iteration   2: 10.723 ops/ms
Iteration   3: 10.454 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.486 ±(99.9%) 4.074 ops/ms [Average]
  (min, avg, max) = (10.280, 10.486, 10.723), stdev = 0.223
  CI (99.9%): [6.412, 14.560] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:53
# Fork: 1 of 1
# Warmup Iteration   1: 6.965 ops/ms
# Warmup Iteration   2: 9.856 ops/ms
# Warmup Iteration   3: 10.098 ops/ms
Iteration   1: 9.836 ops/ms
Iteration   2: 9.870 ops/ms
Iteration   3: 10.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  9.970 ±(99.9%) 3.709 ops/ms [Average]
  (min, avg, max) = (9.836, 9.970, 10.204), stdev = 0.203
  CI (99.9%): [6.261, 13.678] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.753 ops/ms
# Warmup Iteration   2: 7.549 ops/ms
# Warmup Iteration   3: 7.772 ops/ms
Iteration   1: 7.959 ops/ms
Iteration   2: 7.910 ops/ms
Iteration   3: 8.033 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.967 ±(99.9%) 1.125 ops/ms [Average]
  (min, avg, max) = (7.910, 7.967, 8.033), stdev = 0.062
  CI (99.9%): [6.842, 9.093] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.311 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.291 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.175 ±(99.9%) 0.002 ms/op
Iteration   1: 3.182 ±(99.9%) 0.002 ms/op
Iteration   2: 3.209 ±(99.9%) 0.002 ms/op
Iteration   3: 3.136 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.176 ±(99.9%) 0.677 ms/op [Average]
  (min, avg, max) = (3.136, 3.176, 3.209), stdev = 0.037
  CI (99.9%): [2.498, 3.853] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 3.135 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.003 ms/op
Iteration   1: 3.122 ±(99.9%) 0.002 ms/op
Iteration   2: 3.038 ±(99.9%) 0.002 ms/op
Iteration   3: 2.988 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.049 ±(99.9%) 1.239 ms/op [Average]
  (min, avg, max) = (2.988, 3.049, 3.122), stdev = 0.068
  CI (99.9%): [1.810, 4.289] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.278 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.210 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.105 ±(99.9%) 0.003 ms/op
Iteration   1: 3.191 ±(99.9%) 0.002 ms/op
Iteration   2: 3.137 ±(99.9%) 0.001 ms/op
Iteration   3: 3.162 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.163 ±(99.9%) 0.492 ms/op [Average]
  (min, avg, max) = (3.137, 3.163, 3.191), stdev = 0.027
  CI (99.9%): [2.671, 3.655] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.727 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.314 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.025 ±(99.9%) 0.011 ms/op
Iteration   1: 4.027 ±(99.9%) 0.012 ms/op
Iteration   2: 3.960 ±(99.9%) 0.008 ms/op
Iteration   3: 4.066 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.018 ±(99.9%) 0.984 ms/op [Average]
  (min, avg, max) = (3.960, 4.018, 4.066), stdev = 0.054
  CI (99.9%): [3.034, 5.001] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.304 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.160 ±(99.9%) 0.006 ms/op
Iteration   1: 3.091 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.607 ms/op
                 createUser·p0.50:   3.109 ms/op
                 createUser·p0.90:   3.789 ms/op
                 createUser·p0.95:   3.981 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  7.442 ms/op
                 createUser·p0.9999: 16.930 ms/op
                 createUser·p1.00:   18.219 ms/op

Iteration   2: 3.130 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.833 ms/op
                 createUser·p0.50:   3.113 ms/op
                 createUser·p0.90:   3.752 ms/op
                 createUser·p0.95:   3.953 ms/op
                 createUser·p0.99:   4.276 ms/op
                 createUser·p0.999:  6.729 ms/op
                 createUser·p0.9999: 20.571 ms/op
                 createUser·p1.00:   21.987 ms/op

Iteration   3: 3.222 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.885 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   4.018 ms/op
                 createUser·p0.95:   4.194 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  8.560 ms/op
                 createUser·p0.9999: 21.660 ms/op
                 createUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305091
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29788 
    [ 2.500,  5.000) = 274063 
    [ 5.000,  7.500) = 943 
    [ 7.500, 10.000) = 88 
    [10.000, 12.500) = 17 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.607 ms/op
     p(50.0000) =      3.146 ms/op
     p(90.0000) =      3.871 ms/op
     p(95.0000) =      4.063 ms/op
     p(99.0000) =      4.432 ms/op
     p(99.9000) =      7.454 ms/op
     p(99.9900) =     20.742 ms/op
     p(99.9990) =     21.886 ms/op
     p(99.9999) =     21.987 ms/op
    p(100.0000) =     21.987 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.088 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.182 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.006 ms/op
Iteration   1: 3.122 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.844 ms/op
                 existUser·p0.50:   3.105 ms/op
                 existUser·p0.90:   3.768 ms/op
                 existUser·p0.95:   3.924 ms/op
                 existUser·p0.99:   4.260 ms/op
                 existUser·p0.999:  6.468 ms/op
                 existUser·p0.9999: 13.283 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.271 ms/op
                 existUser·p0.50:   3.019 ms/op
                 existUser·p0.90:   3.654 ms/op
                 existUser·p0.95:   3.842 ms/op
                 existUser·p0.99:   4.276 ms/op
                 existUser·p0.999:  8.965 ms/op
                 existUser·p0.9999: 14.186 ms/op
                 existUser·p1.00:   14.451 ms/op

Iteration   3: 3.045 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.820 ms/op
                 existUser·p0.50:   3.072 ms/op
                 existUser·p0.90:   3.736 ms/op
                 existUser·p0.95:   3.883 ms/op
                 existUser·p0.99:   4.235 ms/op
                 existUser·p0.999:  6.807 ms/op
                 existUser·p0.9999: 17.138 ms/op
                 existUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 313348
  mean =      3.063 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1362 
    [ 1.250,  2.500) = 36252 
    [ 2.500,  3.750) = 247252 
    [ 3.750,  5.000) = 27400 
    [ 5.000,  6.250) = 453 
    [ 6.250,  7.500) = 290 
    [ 7.500,  8.750) = 102 
    [ 8.750, 10.000) = 77 
    [10.000, 11.250) = 7 
    [11.250, 12.500) = 28 
    [12.500, 13.750) = 55 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 3 
    [16.250, 17.500) = 16 
    [17.500, 18.750) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.271 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.723 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.252 ms/op
     p(99.9000) =      8.012 ms/op
     p(99.9900) =     14.533 ms/op
     p(99.9990) =     17.465 ms/op
     p(99.9999) =     17.531 ms/op
    p(100.0000) =     17.531 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.237 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.249 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.174 ±(99.9%) 0.007 ms/op
Iteration   1: 3.188 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.049 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   4.628 ms/op
                 getUser·p0.999:  6.113 ms/op
                 getUser·p0.9999: 14.106 ms/op
                 getUser·p1.00:   14.615 ms/op

Iteration   2: 3.215 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.937 ms/op
                 getUser·p0.50:   3.178 ms/op
                 getUser·p0.90:   3.908 ms/op
                 getUser·p0.95:   4.092 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.152 ms/op
                 getUser·p0.9999: 14.927 ms/op
                 getUser·p1.00:   15.319 ms/op

Iteration   3: 3.226 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.863 ms/op
                 getUser·p0.50:   3.195 ms/op
                 getUser·p0.90:   3.903 ms/op
                 getUser·p0.95:   4.084 ms/op
                 getUser·p0.99:   4.415 ms/op
                 getUser·p0.999:  7.265 ms/op
                 getUser·p0.9999: 18.225 ms/op
                 getUser·p1.00:   18.711 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 298986
  mean =      3.210 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 236 
    [ 1.250,  2.500) = 18063 
    [ 2.500,  3.750) = 234475 
    [ 3.750,  5.000) = 44945 
    [ 5.000,  6.250) = 758 
    [ 6.250,  7.500) = 277 
    [ 7.500,  8.750) = 72 
    [ 8.750, 10.000) = 0 
    [10.000, 11.250) = 0 
    [11.250, 12.500) = 6 
    [12.500, 13.750) = 30 
    [13.750, 15.000) = 53 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 48 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.863 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.899 ms/op
     p(95.0000) =      4.092 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.103 ms/op
     p(99.9900) =     17.272 ms/op
     p(99.9990) =     18.613 ms/op
     p(99.9999) =     18.711 ms/op
    p(100.0000) =     18.711 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 5.495 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 4.258 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.187 ±(99.9%) 0.012 ms/op
Iteration   1: 4.065 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   5.276 ms/op
                 listUser·p0.95:   5.906 ms/op
                 listUser·p0.99:   7.324 ms/op
                 listUser·p0.999:  14.413 ms/op
                 listUser·p0.9999: 19.611 ms/op
                 listUser·p1.00:   20.709 ms/op

Iteration   2: 4.114 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.294 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   5.259 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  17.047 ms/op
                 listUser·p0.9999: 23.426 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.174 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.930 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   5.325 ms/op
                 listUser·p0.95:   5.988 ms/op
                 listUser·p0.99:   7.101 ms/op
                 listUser·p0.999:  18.544 ms/op
                 listUser·p0.9999: 28.388 ms/op
                 listUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 233047
  mean =      4.117 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1959 
    [ 2.500,  5.000) = 199953 
    [ 5.000,  7.500) = 29476 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 107 
    [12.500, 15.000) = 148 
    [15.000, 17.500) = 105 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 53 
    [25.000, 27.500) = 11 

  Percentiles, ms/op:
      p(0.0000) =      0.930 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      5.284 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      7.184 ms/op
     p(99.9000) =     16.088 ms/op
     p(99.9900) =     27.613 ms/op
     p(99.9990) =     28.782 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.173 ± 3.717  ops/ms
ClientGrpc.existUser                       thrpt       3  10.486 ± 4.074  ops/ms
ClientGrpc.getUser                         thrpt       3   9.970 ± 3.709  ops/ms
ClientGrpc.listUser                        thrpt       3   7.967 ± 1.125  ops/ms
ClientGrpc.createUser                       avgt       3   3.176 ± 0.677   ms/op
ClientGrpc.existUser                        avgt       3   3.049 ± 1.239   ms/op
ClientGrpc.getUser                          avgt       3   3.163 ± 0.492   ms/op
ClientGrpc.listUser                         avgt       3   4.018 ± 0.984   ms/op
ClientGrpc.createUser                     sample  305091   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.607           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.146           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.871           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.063           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.454           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.742           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.987           ms/op
ClientGrpc.existUser                      sample  313348   3.063 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.271           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.064           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.723           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.887           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.252           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.012           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.533           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.531           ms/op
ClientGrpc.getUser                        sample  298986   3.210 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.863           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.174           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.899           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.092           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.103           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.272           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.711           ms/op
ClientGrpc.listUser                       sample  233047   4.117 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.930           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.924           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.284           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.898           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.184           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.088           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.613           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.869           ms/op
