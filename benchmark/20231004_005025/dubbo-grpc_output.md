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
# Warmup Iteration   1: 4.212 ops/ms
# Warmup Iteration   2: 8.622 ops/ms
# Warmup Iteration   3: 9.929 ops/ms
Iteration   1: 9.998 ops/ms
Iteration   2: 10.265 ops/ms
Iteration   3: 10.250 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.171 ±(99.9%) 2.740 ops/ms [Average]
  (min, avg, max) = (9.998, 10.171, 10.265), stdev = 0.150
  CI (99.9%): [7.432, 12.911] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 7.275 ops/ms
# Warmup Iteration   2: 10.240 ops/ms
# Warmup Iteration   3: 10.954 ops/ms
Iteration   1: 10.750 ops/ms
Iteration   2: 10.807 ops/ms
Iteration   3: 11.224 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.927 ±(99.9%) 4.717 ops/ms [Average]
  (min, avg, max) = (10.750, 10.927, 11.224), stdev = 0.259
  CI (99.9%): [6.210, 15.644] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.047 ops/ms
# Warmup Iteration   2: 9.783 ops/ms
# Warmup Iteration   3: 10.368 ops/ms
Iteration   1: 10.080 ops/ms
Iteration   2: 10.310 ops/ms
Iteration   3: 10.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.240 ±(99.9%) 2.536 ops/ms [Average]
  (min, avg, max) = (10.080, 10.240, 10.330), stdev = 0.139
  CI (99.9%): [7.704, 12.776] (assumes normal distribution)


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
# Warmup Iteration   1: 5.214 ops/ms
# Warmup Iteration   2: 7.619 ops/ms
# Warmup Iteration   3: 8.130 ops/ms
Iteration   1: 8.228 ops/ms
Iteration   2: 8.452 ops/ms
Iteration   3: 8.100 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.260 ±(99.9%) 3.256 ops/ms [Average]
  (min, avg, max) = (8.100, 8.260, 8.452), stdev = 0.178
  CI (99.9%): [5.004, 11.517] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.170 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.235 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.145 ±(99.9%) 0.002 ms/op
Iteration   1: 3.152 ±(99.9%) 0.002 ms/op
Iteration   2: 3.106 ±(99.9%) 0.001 ms/op
Iteration   3: 3.137 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.131 ±(99.9%) 0.429 ms/op [Average]
  (min, avg, max) = (3.106, 3.131, 3.152), stdev = 0.023
  CI (99.9%): [2.703, 3.560] (assumes normal distribution)


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
# Warmup Iteration   1: 3.890 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.077 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.981 ±(99.9%) 0.003 ms/op
Iteration   1: 2.971 ±(99.9%) 0.002 ms/op
Iteration   2: 2.962 ±(99.9%) 0.001 ms/op
Iteration   3: 3.002 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.978 ±(99.9%) 0.381 ms/op [Average]
  (min, avg, max) = (2.962, 2.978, 3.002), stdev = 0.021
  CI (99.9%): [2.597, 3.359] (assumes normal distribution)


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
# Warmup Iteration   1: 4.179 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.276 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.209 ±(99.9%) 0.002 ms/op
Iteration   1: 3.134 ±(99.9%) 0.002 ms/op
Iteration   2: 3.103 ±(99.9%) 0.002 ms/op
Iteration   3: 3.075 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.104 ±(99.9%) 0.536 ms/op [Average]
  (min, avg, max) = (3.075, 3.104, 3.134), stdev = 0.029
  CI (99.9%): [2.568, 3.640] (assumes normal distribution)


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
# Warmup Iteration   1: 5.182 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 4.075 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.964 ±(99.9%) 0.020 ms/op
Iteration   1: 3.882 ±(99.9%) 0.015 ms/op
Iteration   2: 3.849 ±(99.9%) 0.018 ms/op
Iteration   3: 3.878 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.870 ±(99.9%) 0.334 ms/op [Average]
  (min, avg, max) = (3.849, 3.870, 3.882), stdev = 0.018
  CI (99.9%): [3.536, 4.203] (assumes normal distribution)


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
# Warmup Iteration   1: 4.591 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.307 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.131 ±(99.9%) 0.007 ms/op
Iteration   1: 3.119 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.432 ms/op
                 createUser·p0.999:  6.807 ms/op
                 createUser·p0.9999: 14.221 ms/op
                 createUser·p1.00:   14.713 ms/op

Iteration   2: 3.098 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   1.071 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.284 ms/op
                 createUser·p0.999:  7.404 ms/op
                 createUser·p0.9999: 14.037 ms/op
                 createUser·p1.00:   14.811 ms/op

Iteration   3: 3.113 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.850 ms/op
                 createUser·p0.50:   3.072 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.711 ms/op
                 createUser·p0.99:   4.309 ms/op
                 createUser·p0.999:  11.316 ms/op
                 createUser·p0.9999: 15.560 ms/op
                 createUser·p1.00:   15.827 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308412
  mean =      3.110 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 70 
    [ 1.250,  2.500) = 9467 
    [ 2.500,  3.750) = 281209 
    [ 3.750,  5.000) = 16094 
    [ 5.000,  6.250) = 905 
    [ 6.250,  7.500) = 310 
    [ 7.500,  8.750) = 93 
    [ 8.750, 10.000) = 7 
    [10.000, 11.250) = 24 
    [11.250, 12.500) = 60 
    [12.500, 13.750) = 71 
    [13.750, 15.000) = 80 
    [15.000, 16.250) = 22 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.850 ms/op
     p(50.0000) =      3.064 ms/op
     p(90.0000) =      3.613 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.262 ms/op
     p(99.9900) =     14.860 ms/op
     p(99.9990) =     15.679 ms/op
     p(99.9999) =     15.827 ms/op
    p(100.0000) =     15.827 ms/op


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
# Warmup Iteration   1: 4.063 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.134 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.001 ±(99.9%) 0.005 ms/op
Iteration   1: 3.012 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.656 ms/op
                 existUser·p0.50:   2.966 ms/op
                 existUser·p0.90:   3.486 ms/op
                 existUser·p0.95:   3.662 ms/op
                 existUser·p0.99:   4.135 ms/op
                 existUser·p0.999:  8.000 ms/op
                 existUser·p0.9999: 12.780 ms/op
                 existUser·p1.00:   13.009 ms/op

Iteration   2: 3.019 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.780 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.748 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  7.301 ms/op
                 existUser·p0.9999: 20.671 ms/op
                 existUser·p1.00:   21.201 ms/op

Iteration   3: 2.967 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.412 ms/op
                 existUser·p0.95:   3.592 ms/op
                 existUser·p0.99:   4.133 ms/op
                 existUser·p0.999:  11.126 ms/op
                 existUser·p0.9999: 17.177 ms/op
                 existUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 320104
  mean =      2.999 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24009 
    [ 2.500,  5.000) = 294646 
    [ 5.000,  7.500) = 1026 
    [ 7.500, 10.000) = 199 
    [10.000, 12.500) = 73 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 4 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.656 ms/op
     p(50.0000) =      2.966 ms/op
     p(90.0000) =      3.478 ms/op
     p(95.0000) =      3.670 ms/op
     p(99.0000) =      4.190 ms/op
     p(99.9000) =      8.002 ms/op
     p(99.9900) =     19.831 ms/op
     p(99.9990) =     21.057 ms/op
     p(99.9999) =     21.201 ms/op
    p(100.0000) =     21.201 ms/op


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
# Warmup Iteration   1: 4.324 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.154 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.152 ±(99.9%) 0.007 ms/op
Iteration   1: 3.080 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.939 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.506 ms/op
                 getUser·p0.95:   3.731 ms/op
                 getUser·p0.99:   4.268 ms/op
                 getUser·p0.999:  8.988 ms/op
                 getUser·p0.9999: 13.353 ms/op
                 getUser·p1.00:   13.861 ms/op

Iteration   2: 3.214 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   1.029 ms/op
                 getUser·p0.50:   3.174 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   3.944 ms/op
                 getUser·p0.99:   4.334 ms/op
                 getUser·p0.999:  7.336 ms/op
                 getUser·p0.9999: 13.861 ms/op
                 getUser·p1.00:   14.025 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  7.239 ms/op
                 getUser·p0.9999: 24.969 ms/op
                 getUser·p1.00:   26.739 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 307192
  mean =      3.126 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6403 
    [ 2.500,  5.000) = 299172 
    [ 5.000,  7.500) = 1261 
    [ 7.500, 10.000) = 125 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 145 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      0.649 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.695 ms/op
     p(95.0000) =      3.887 ms/op
     p(99.0000) =      4.342 ms/op
     p(99.9000) =      8.100 ms/op
     p(99.9900) =     24.150 ms/op
     p(99.9990) =     25.295 ms/op
     p(99.9999) =     26.739 ms/op
    p(100.0000) =     26.739 ms/op


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
# Warmup Iteration   1: 5.416 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.995 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.009 ms/op
Iteration   1: 3.976 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.520 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.612 ms/op
                 listUser·p0.95:   5.652 ms/op
                 listUser·p0.99:   6.685 ms/op
                 listUser·p0.999:  11.619 ms/op
                 listUser·p0.9999: 14.725 ms/op
                 listUser·p1.00:   15.319 ms/op

Iteration   2: 3.808 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.507 ms/op
                 listUser·p0.50:   3.731 ms/op
                 listUser·p0.90:   4.383 ms/op
                 listUser·p0.95:   5.202 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  13.485 ms/op
                 listUser·p0.9999: 16.830 ms/op
                 listUser·p1.00:   17.629 ms/op

Iteration   3: 3.945 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.415 ms/op
                 listUser·p0.50:   3.854 ms/op
                 listUser·p0.90:   4.415 ms/op
                 listUser·p0.95:   4.964 ms/op
                 listUser·p0.99:   6.717 ms/op
                 listUser·p0.999:  14.483 ms/op
                 listUser·p0.9999: 23.589 ms/op
                 listUser·p1.00:   24.412 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245716
  mean =      3.908 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1977 
    [ 2.500,  5.000) = 229161 
    [ 5.000,  7.500) = 13648 
    [ 7.500, 10.000) = 503 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 71 
    [17.500, 20.000) = 5 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.415 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.465 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     13.292 ms/op
     p(99.9900) =     22.338 ms/op
     p(99.9990) =     24.201 ms/op
     p(99.9999) =     24.412 ms/op
    p(100.0000) =     24.412 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.171 ± 2.740  ops/ms
ClientGrpc.existUser                       thrpt       3  10.927 ± 4.717  ops/ms
ClientGrpc.getUser                         thrpt       3  10.240 ± 2.536  ops/ms
ClientGrpc.listUser                        thrpt       3   8.260 ± 3.256  ops/ms
ClientGrpc.createUser                       avgt       3   3.131 ± 0.429   ms/op
ClientGrpc.existUser                        avgt       3   2.978 ± 0.381   ms/op
ClientGrpc.getUser                          avgt       3   3.104 ± 0.536   ms/op
ClientGrpc.listUser                         avgt       3   3.870 ± 0.334   ms/op
ClientGrpc.createUser                     sample  308412   3.110 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.850           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.064           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.613           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.781           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.262           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.860           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.827           ms/op
ClientGrpc.existUser                      sample  320104   2.999 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.656           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.966           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.478           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.670           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.190           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.002           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.831           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.201           ms/op
ClientGrpc.getUser                        sample  307192   3.126 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.649           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.072           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.695           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.887           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.342           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.100           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.150           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.739           ms/op
ClientGrpc.listUser                       sample  245716   3.908 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.415           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.465           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.218           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.660           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.292           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.338           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.412           ms/op
