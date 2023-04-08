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
# Warmup Iteration   1: 3.542 ops/ms
# Warmup Iteration   2: 8.504 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 10.115 ops/ms
Iteration   2: 10.327 ops/ms
Iteration   3: 10.327 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.256 ±(99.9%) 2.235 ops/ms [Average]
  (min, avg, max) = (10.115, 10.256, 10.327), stdev = 0.122
  CI (99.9%): [8.021, 12.491] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.226 ops/ms
# Warmup Iteration   2: 10.192 ops/ms
# Warmup Iteration   3: 10.724 ops/ms
Iteration   1: 10.720 ops/ms
Iteration   2: 10.673 ops/ms
Iteration   3: 10.963 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.785 ±(99.9%) 2.831 ops/ms [Average]
  (min, avg, max) = (10.673, 10.785, 10.963), stdev = 0.155
  CI (99.9%): [7.954, 13.617] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.621 ops/ms
# Warmup Iteration   2: 9.604 ops/ms
# Warmup Iteration   3: 10.280 ops/ms
Iteration   1: 10.447 ops/ms
Iteration   2: 10.145 ops/ms
Iteration   3: 10.133 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.242 ±(99.9%) 3.248 ops/ms [Average]
  (min, avg, max) = (10.133, 10.242, 10.447), stdev = 0.178
  CI (99.9%): [6.994, 13.489] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:47
# Fork: 1 of 1
# Warmup Iteration   1: 5.046 ops/ms
# Warmup Iteration   2: 7.337 ops/ms
# Warmup Iteration   3: 7.624 ops/ms
Iteration   1: 7.850 ops/ms
Iteration   2: 8.215 ops/ms
Iteration   3: 7.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.907 ±(99.9%) 5.178 ops/ms [Average]
  (min, avg, max) = (7.656, 7.907, 8.215), stdev = 0.284
  CI (99.9%): [2.729, 13.085] (assumes normal distribution)


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
# Warmup Iteration   1: 4.433 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.154 ±(99.9%) 0.007 ms/op
Iteration   1: 3.103 ±(99.9%) 0.003 ms/op
Iteration   2: 3.175 ±(99.9%) 0.002 ms/op
Iteration   3: 3.054 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.110 ±(99.9%) 1.109 ms/op [Average]
  (min, avg, max) = (3.054, 3.110, 3.175), stdev = 0.061
  CI (99.9%): [2.001, 4.219] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 4.121 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.112 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.966 ±(99.9%) 0.005 ms/op
Iteration   1: 3.028 ±(99.9%) 0.004 ms/op
Iteration   2: 3.018 ±(99.9%) 0.003 ms/op
Iteration   3: 3.041 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.029 ±(99.9%) 0.216 ms/op [Average]
  (min, avg, max) = (3.018, 3.029, 3.041), stdev = 0.012
  CI (99.9%): [2.813, 3.245] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:31
# Fork: 1 of 1
# Warmup Iteration   1: 4.111 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.263 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.002 ms/op
Iteration   1: 3.208 ±(99.9%) 0.003 ms/op
Iteration   2: 3.131 ±(99.9%) 0.002 ms/op
Iteration   3: 3.194 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.178 ±(99.9%) 0.750 ms/op [Average]
  (min, avg, max) = (3.131, 3.178, 3.208), stdev = 0.041
  CI (99.9%): [2.427, 3.928] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:26
# Fork: 1 of 1
# Warmup Iteration   1: 5.677 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.355 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.184 ±(99.9%) 0.033 ms/op
Iteration   1: 4.094 ±(99.9%) 0.007 ms/op
Iteration   2: 4.072 ±(99.9%) 0.024 ms/op
Iteration   3: 4.051 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.072 ±(99.9%) 0.390 ms/op [Average]
  (min, avg, max) = (4.051, 4.072, 4.094), stdev = 0.021
  CI (99.9%): [3.682, 4.463] (assumes normal distribution)


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
# Warmup Iteration   1: 4.593 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 3.267 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.141 ±(99.9%) 0.008 ms/op
Iteration   1: 3.155 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.924 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.756 ms/op
                 createUser·p0.95:   4.076 ms/op
                 createUser·p0.99:   4.932 ms/op
                 createUser·p0.999:  9.068 ms/op
                 createUser·p0.9999: 20.120 ms/op
                 createUser·p1.00:   20.513 ms/op

Iteration   2: 3.167 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.901 ms/op
                 createUser·p0.50:   3.101 ms/op
                 createUser·p0.90:   3.777 ms/op
                 createUser·p0.95:   3.985 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  8.730 ms/op
                 createUser·p0.9999: 23.691 ms/op
                 createUser·p1.00:   23.757 ms/op

Iteration   3: 3.119 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.965 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  12.330 ms/op
                 createUser·p0.9999: 24.920 ms/op
                 createUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 305050
  mean =      3.147 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15305 
    [ 2.500,  5.000) = 287089 
    [ 5.000,  7.500) = 2021 
    [ 7.500, 10.000) = 346 
    [10.000, 12.500) = 93 
    [12.500, 15.000) = 30 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 19 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 80 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.084 ms/op
     p(90.0000) =      3.727 ms/op
     p(95.0000) =      4.006 ms/op
     p(99.0000) =      4.891 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     23.691 ms/op
     p(99.9990) =     25.359 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


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
# Warmup Iteration   1: 4.112 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.253 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.046 ±(99.9%) 0.007 ms/op
Iteration   1: 3.021 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.758 ms/op
                 existUser·p0.50:   2.998 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.785 ms/op
                 existUser·p0.99:   4.727 ms/op
                 existUser·p0.999:  9.079 ms/op
                 existUser·p0.9999: 13.982 ms/op
                 existUser·p1.00:   14.467 ms/op

Iteration   2: 3.024 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.757 ms/op
                 existUser·p0.50:   2.982 ms/op
                 existUser·p0.90:   3.523 ms/op
                 existUser·p0.95:   3.718 ms/op
                 existUser·p0.99:   4.620 ms/op
                 existUser·p0.999:  7.222 ms/op
                 existUser·p0.9999: 23.986 ms/op
                 existUser·p1.00:   24.281 ms/op

Iteration   3: 2.994 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.854 ms/op
                 existUser·p0.50:   2.953 ms/op
                 existUser·p0.90:   3.400 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  6.824 ms/op
                 existUser·p0.9999: 19.998 ms/op
                 existUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 318542
  mean =      3.013 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22441 
    [ 2.500,  5.000) = 294531 
    [ 5.000,  7.500) = 1283 
    [ 7.500, 10.000) = 82 
    [10.000, 12.500) = 45 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.502 ms/op
     p(95.0000) =      3.699 ms/op
     p(99.0000) =      4.506 ms/op
     p(99.9000) =      7.295 ms/op
     p(99.9900) =     23.275 ms/op
     p(99.9990) =     24.216 ms/op
     p(99.9999) =     24.281 ms/op
    p(100.0000) =     24.281 ms/op


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
# Warmup Iteration   1: 4.201 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.491 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.176 ±(99.9%) 0.007 ms/op
Iteration   1: 3.185 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.682 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.768 ms/op
                 getUser·p0.95:   4.055 ms/op
                 getUser·p0.99:   4.989 ms/op
                 getUser·p0.999:  11.323 ms/op
                 getUser·p0.9999: 14.254 ms/op
                 getUser·p1.00:   14.844 ms/op

Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.678 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.661 ms/op
                 getUser·p0.999:  9.912 ms/op
                 getUser·p0.9999: 17.400 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.139 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.898 ms/op
                 getUser·p0.50:   3.121 ms/op
                 getUser·p0.90:   3.674 ms/op
                 getUser·p0.95:   3.871 ms/op
                 getUser·p0.99:   4.456 ms/op
                 getUser·p0.999:  7.031 ms/op
                 getUser·p0.9999: 20.251 ms/op
                 getUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 303298
  mean =      3.165 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13714 
    [ 2.500,  5.000) = 287395 
    [ 5.000,  7.500) = 1688 
    [ 7.500, 10.000) = 174 
    [10.000, 12.500) = 120 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 40 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.682 ms/op
     p(50.0000) =      3.129 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      3.928 ms/op
     p(99.0000) =      4.727 ms/op
     p(99.9000) =     10.453 ms/op
     p(99.9900) =     19.584 ms/op
     p(99.9990) =     20.512 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 5.282 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.499 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.013 ms/op
Iteration   1: 4.177 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   5.292 ms/op
                 listUser·p0.95:   6.078 ms/op
                 listUser·p0.99:   7.586 ms/op
                 listUser·p0.999:  14.914 ms/op
                 listUser·p0.9999: 19.934 ms/op
                 listUser·p1.00:   20.218 ms/op

Iteration   2: 4.108 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.139 ms/op
                 listUser·p0.50:   3.887 ms/op
                 listUser·p0.90:   5.407 ms/op
                 listUser·p0.95:   6.144 ms/op
                 listUser·p0.99:   7.651 ms/op
                 listUser·p0.999:  16.720 ms/op
                 listUser·p0.9999: 22.807 ms/op
                 listUser·p1.00:   24.117 ms/op

Iteration   3: 4.158 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   0.845 ms/op
                 listUser·p0.50:   3.944 ms/op
                 listUser·p0.90:   5.358 ms/op
                 listUser·p0.95:   6.087 ms/op
                 listUser·p0.99:   7.610 ms/op
                 listUser·p0.999:  17.105 ms/op
                 listUser·p0.9999: 21.156 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 231449
  mean =      4.148 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1761 
    [ 2.500,  5.000) = 198123 
    [ 5.000,  7.500) = 28991 
    [ 7.500, 10.000) = 2008 
    [10.000, 12.500) = 167 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 148 
    [17.500, 20.000) = 86 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      5.349 ms/op
     p(95.0000) =      6.103 ms/op
     p(99.0000) =      7.610 ms/op
     p(99.9000) =     16.286 ms/op
     p(99.9900) =     22.512 ms/op
     p(99.9990) =     24.009 ms/op
     p(99.9999) =     24.117 ms/op
    p(100.0000) =     24.117 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.256 ± 2.235  ops/ms
ClientGrpc.existUser                       thrpt       3  10.785 ± 2.831  ops/ms
ClientGrpc.getUser                         thrpt       3  10.242 ± 3.248  ops/ms
ClientGrpc.listUser                        thrpt       3   7.907 ± 5.178  ops/ms
ClientGrpc.createUser                       avgt       3   3.110 ± 1.109   ms/op
ClientGrpc.existUser                        avgt       3   3.029 ± 0.216   ms/op
ClientGrpc.getUser                          avgt       3   3.178 ± 0.750   ms/op
ClientGrpc.listUser                         avgt       3   4.072 ± 0.390   ms/op
ClientGrpc.createUser                     sample  305050   3.147 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.345           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.084           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.727           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.006           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.891           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.650           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.691           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.018           ms/op
ClientGrpc.existUser                      sample  318542   3.013 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.757           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.978           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.502           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.699           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.506           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.295           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.275           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.281           ms/op
ClientGrpc.getUser                        sample  303298   3.165 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.682           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.129           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.703           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.928           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.727           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.453           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.584           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.611           ms/op
ClientGrpc.listUser                       sample  231449   4.148 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.845           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.940           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.349           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.103           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.610           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.286           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.512           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          24.117           ms/op
