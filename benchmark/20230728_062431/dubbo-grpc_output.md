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
# Warmup Iteration   1: 2.318 ops/ms
# Warmup Iteration   2: 5.778 ops/ms
# Warmup Iteration   3: 7.181 ops/ms
Iteration   1: 7.604 ops/ms
Iteration   2: 7.722 ops/ms
Iteration   3: 7.906 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.744 ±(99.9%) 2.775 ops/ms [Average]
  (min, avg, max) = (7.604, 7.744, 7.906), stdev = 0.152
  CI (99.9%): [4.969, 10.518] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 5.048 ops/ms
# Warmup Iteration   2: 7.538 ops/ms
# Warmup Iteration   3: 8.072 ops/ms
Iteration   1: 8.265 ops/ms
Iteration   2: 8.318 ops/ms
Iteration   3: 8.675 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.419 ±(99.9%) 4.066 ops/ms [Average]
  (min, avg, max) = (8.265, 8.419, 8.675), stdev = 0.223
  CI (99.9%): [4.353, 12.486] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 4.973 ops/ms
# Warmup Iteration   2: 7.299 ops/ms
# Warmup Iteration   3: 7.596 ops/ms
Iteration   1: 7.719 ops/ms
Iteration   2: 8.035 ops/ms
Iteration   3: 8.129 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.961 ±(99.9%) 3.923 ops/ms [Average]
  (min, avg, max) = (7.719, 7.961, 8.129), stdev = 0.215
  CI (99.9%): [4.038, 11.884] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 3.839 ops/ms
# Warmup Iteration   2: 5.659 ops/ms
# Warmup Iteration   3: 5.905 ops/ms
Iteration   1: 5.955 ops/ms
Iteration   2: 6.102 ops/ms
Iteration   3: 6.465 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.174 ±(99.9%) 4.786 ops/ms [Average]
  (min, avg, max) = (5.955, 6.174, 6.465), stdev = 0.262
  CI (99.9%): [1.388, 10.960] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.969 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.205 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.229 ±(99.9%) 0.010 ms/op
Iteration   1: 4.221 ±(99.9%) 0.002 ms/op
Iteration   2: 4.253 ±(99.9%) 0.003 ms/op
Iteration   3: 4.287 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.254 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (4.221, 4.254, 4.287), stdev = 0.033
  CI (99.9%): [3.658, 4.849] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.148 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.331 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.008 ms/op
Iteration   1: 3.968 ±(99.9%) 0.004 ms/op
Iteration   2: 4.109 ±(99.9%) 0.003 ms/op
Iteration   3: 4.110 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.062 ±(99.9%) 1.494 ms/op [Average]
  (min, avg, max) = (3.968, 4.062, 4.110), stdev = 0.082
  CI (99.9%): [2.568, 5.556] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 6.399 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.594 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.647 ±(99.9%) 0.005 ms/op
Iteration   1: 4.368 ±(99.9%) 0.006 ms/op
Iteration   2: 4.360 ±(99.9%) 0.003 ms/op
Iteration   3: 4.140 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.289 ±(99.9%) 2.368 ms/op [Average]
  (min, avg, max) = (4.140, 4.289, 4.368), stdev = 0.130
  CI (99.9%): [1.921, 6.657] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.791 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 5.749 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.567 ±(99.9%) 0.020 ms/op
Iteration   1: 5.522 ±(99.9%) 0.019 ms/op
Iteration   2: 5.478 ±(99.9%) 0.027 ms/op
Iteration   3: 5.480 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.494 ±(99.9%) 0.456 ms/op [Average]
  (min, avg, max) = (5.478, 5.494, 5.522), stdev = 0.025
  CI (99.9%): [5.037, 5.950] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.801 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 4.465 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.285 ±(99.9%) 0.013 ms/op
Iteration   1: 3.991 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.102 ms/op
                 createUser·p0.50:   3.879 ms/op
                 createUser·p0.90:   4.997 ms/op
                 createUser·p0.95:   5.464 ms/op
                 createUser·p0.99:   6.936 ms/op
                 createUser·p0.999:  10.781 ms/op
                 createUser·p0.9999: 15.057 ms/op
                 createUser·p1.00:   15.286 ms/op

Iteration   2: 4.184 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.186 ms/op
                 createUser·p0.95:   5.587 ms/op
                 createUser·p0.99:   7.386 ms/op
                 createUser·p0.999:  11.953 ms/op
                 createUser·p0.9999: 17.882 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   3: 4.098 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.979 ms/op
                 createUser·p0.50:   3.969 ms/op
                 createUser·p0.90:   5.104 ms/op
                 createUser·p0.95:   5.538 ms/op
                 createUser·p0.99:   7.168 ms/op
                 createUser·p0.999:  17.170 ms/op
                 createUser·p0.9999: 19.536 ms/op
                 createUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 234559
  mean =      4.090 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2490 
    [ 2.500,  5.000) = 204179 
    [ 5.000,  7.500) = 25974 
    [ 7.500, 10.000) = 1525 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 110 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.979 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      5.104 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      7.176 ms/op
     p(99.9000) =     12.730 ms/op
     p(99.9900) =     19.071 ms/op
     p(99.9990) =     20.337 ms/op
     p(99.9999) =     20.775 ms/op
    p(100.0000) =     20.775 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.510 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.214 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.011 ms/op
Iteration   1: 3.973 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.090 ms/op
                 existUser·p0.50:   3.879 ms/op
                 existUser·p0.90:   5.005 ms/op
                 existUser·p0.95:   5.423 ms/op
                 existUser·p0.99:   6.750 ms/op
                 existUser·p0.999:  9.683 ms/op
                 existUser·p0.9999: 15.235 ms/op
                 existUser·p1.00:   17.826 ms/op

Iteration   2: 3.872 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.980 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.825 ms/op
                 existUser·p0.95:   5.267 ms/op
                 existUser·p0.99:   6.955 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 24.829 ms/op
                 existUser·p1.00:   26.280 ms/op

Iteration   3: 3.817 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.040 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.292 ms/op
                 existUser·p0.99:   6.513 ms/op
                 existUser·p0.999:  10.928 ms/op
                 existUser·p0.9999: 28.213 ms/op
                 existUser·p1.00:   28.574 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 247096
  mean =      3.887 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6836 
    [ 2.500,  5.000) = 219290 
    [ 5.000,  7.500) = 19492 
    [ 7.500, 10.000) = 1224 
    [10.000, 12.500) = 91 
    [12.500, 15.000) = 50 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      0.980 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.899 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     10.173 ms/op
     p(99.9900) =     27.511 ms/op
     p(99.9990) =     28.493 ms/op
     p(99.9999) =     28.574 ms/op
    p(100.0000) =     28.574 ms/op


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
# Warmup Iteration   1: 6.668 ±(99.9%) 0.073 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.189 ±(99.9%) 0.011 ms/op
Iteration   1: 4.029 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.883 ms/op
                 getUser·p0.50:   3.936 ms/op
                 getUser·p0.90:   5.177 ms/op
                 getUser·p0.95:   5.628 ms/op
                 getUser·p0.99:   6.881 ms/op
                 getUser·p0.999:  11.575 ms/op
                 getUser·p0.9999: 17.367 ms/op
                 getUser·p1.00:   17.760 ms/op

Iteration   2: 4.051 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.102 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   5.120 ms/op
                 getUser·p0.95:   5.554 ms/op
                 getUser·p0.99:   7.242 ms/op
                 getUser·p0.999:  12.140 ms/op
                 getUser·p0.9999: 20.857 ms/op
                 getUser·p1.00:   21.561 ms/op

Iteration   3: 4.210 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.069 ms/op
                 getUser·p0.50:   4.116 ms/op
                 getUser·p0.90:   5.243 ms/op
                 getUser·p0.95:   5.669 ms/op
                 getUser·p0.99:   6.954 ms/op
                 getUser·p0.999:  11.763 ms/op
                 getUser·p0.9999: 22.289 ms/op
                 getUser·p1.00:   22.938 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 234530
  mean =      4.095 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5829 
    [ 2.500,  5.000) = 197632 
    [ 5.000,  7.500) = 29429 
    [ 7.500, 10.000) = 1317 
    [10.000, 12.500) = 134 
    [12.500, 15.000) = 55 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 5 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.883 ms/op
     p(50.0000) =      3.990 ms/op
     p(90.0000) =      5.186 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     11.977 ms/op
     p(99.9900) =     20.183 ms/op
     p(99.9990) =     22.838 ms/op
     p(99.9999) =     22.938 ms/op
    p(100.0000) =     22.938 ms/op


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
# Warmup Iteration   1: 7.352 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.844 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.514 ±(99.9%) 0.023 ms/op
Iteration   1: 5.454 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.450 ms/op
                 listUser·p0.50:   5.194 ms/op
                 listUser·p0.90:   7.094 ms/op
                 listUser·p0.95:   8.028 ms/op
                 listUser·p0.99:   10.273 ms/op
                 listUser·p0.999:  16.985 ms/op
                 listUser·p0.9999: 19.104 ms/op
                 listUser·p1.00:   19.235 ms/op

Iteration   2: 5.521 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.350 ms/op
                 listUser·p0.50:   5.218 ms/op
                 listUser·p0.90:   7.299 ms/op
                 listUser·p0.95:   8.320 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  16.777 ms/op
                 listUser·p0.9999: 20.677 ms/op
                 listUser·p1.00:   21.201 ms/op

Iteration   3: 5.335 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   1.421 ms/op
                 listUser·p0.50:   5.063 ms/op
                 listUser·p0.90:   6.898 ms/op
                 listUser·p0.95:   7.905 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  20.814 ms/op
                 listUser·p0.9999: 23.463 ms/op
                 listUser·p1.00:   23.888 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 176483
  mean =      5.435 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 112 
    [ 2.500,  5.000) = 76213 
    [ 5.000,  7.500) = 86775 
    [ 7.500, 10.000) = 11098 
    [10.000, 12.500) = 1636 
    [12.500, 15.000) = 318 
    [15.000, 17.500) = 147 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 86 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.350 ms/op
     p(50.0000) =      5.153 ms/op
     p(90.0000) =      7.111 ms/op
     p(95.0000) =      8.094 ms/op
     p(99.0000) =     10.371 ms/op
     p(99.9000) =     17.727 ms/op
     p(99.9900) =     21.901 ms/op
     p(99.9990) =     23.888 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.744 ± 2.775  ops/ms
ClientGrpc.existUser                       thrpt       3   8.419 ± 4.066  ops/ms
ClientGrpc.getUser                         thrpt       3   7.961 ± 3.923  ops/ms
ClientGrpc.listUser                        thrpt       3   6.174 ± 4.786  ops/ms
ClientGrpc.createUser                       avgt       3   4.254 ± 0.595   ms/op
ClientGrpc.existUser                        avgt       3   4.062 ± 1.494   ms/op
ClientGrpc.getUser                          avgt       3   4.289 ± 2.368   ms/op
ClientGrpc.listUser                         avgt       3   5.494 ± 0.456   ms/op
ClientGrpc.createUser                     sample  234559   4.090 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.979           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.973           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.104           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.530           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.176           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.730           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.071           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.775           ms/op
ClientGrpc.existUser                      sample  247096   3.887 ± 0.006   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.980           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.781           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.899           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.333           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.742           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.173           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          27.511           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          28.574           ms/op
ClientGrpc.getUser                        sample  234530   4.095 ± 0.007   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.883           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.990           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.186           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.620           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.012           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.977           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.183           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.938           ms/op
ClientGrpc.listUser                       sample  176483   5.435 ± 0.011   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.350           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.153           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.111           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.094           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.371           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.727           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.901           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.888           ms/op
