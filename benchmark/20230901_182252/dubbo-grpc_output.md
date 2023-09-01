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
# Warmup Iteration   1: 1.792 ops/ms
# Warmup Iteration   2: 4.763 ops/ms
# Warmup Iteration   3: 6.381 ops/ms
Iteration   1: 6.541 ops/ms
Iteration   2: 6.914 ops/ms
Iteration   3: 6.810 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.755 ±(99.9%) 3.507 ops/ms [Average]
  (min, avg, max) = (6.541, 6.755, 6.914), stdev = 0.192
  CI (99.9%): [3.248, 10.262] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:09
# Fork: 1 of 1
# Warmup Iteration   1: 4.289 ops/ms
# Warmup Iteration   2: 6.402 ops/ms
# Warmup Iteration   3: 6.854 ops/ms
Iteration   1: 6.925 ops/ms
Iteration   2: 6.927 ops/ms
Iteration   3: 6.821 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  6.891 ±(99.9%) 1.104 ops/ms [Average]
  (min, avg, max) = (6.821, 6.891, 6.927), stdev = 0.061
  CI (99.9%): [5.787, 7.995] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:02
# Fork: 1 of 1
# Warmup Iteration   1: 3.675 ops/ms
# Warmup Iteration   2: 5.948 ops/ms
# Warmup Iteration   3: 6.621 ops/ms
Iteration   1: 6.826 ops/ms
Iteration   2: 6.816 ops/ms
Iteration   3: 6.653 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.765 ±(99.9%) 1.771 ops/ms [Average]
  (min, avg, max) = (6.653, 6.765, 6.826), stdev = 0.097
  CI (99.9%): [4.994, 8.536] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.220 ops/ms
# Warmup Iteration   2: 4.788 ops/ms
# Warmup Iteration   3: 5.117 ops/ms
Iteration   1: 5.199 ops/ms
Iteration   2: 5.254 ops/ms
Iteration   3: 5.195 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.216 ±(99.9%) 0.600 ops/ms [Average]
  (min, avg, max) = (5.195, 5.216, 5.254), stdev = 0.033
  CI (99.9%): [4.615, 5.816] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 7.621 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.242 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.855 ±(99.9%) 0.003 ms/op
Iteration   1: 4.761 ±(99.9%) 0.003 ms/op
Iteration   2: 4.762 ±(99.9%) 0.005 ms/op
Iteration   3: 4.875 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.799 ±(99.9%) 1.198 ms/op [Average]
  (min, avg, max) = (4.761, 4.799, 4.875), stdev = 0.066
  CI (99.9%): [3.601, 5.998] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 6.791 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.807 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.413 ±(99.9%) 0.005 ms/op
Iteration   1: 4.483 ±(99.9%) 0.004 ms/op
Iteration   2: 4.461 ±(99.9%) 0.003 ms/op
Iteration   3: 4.407 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.451 ±(99.9%) 0.716 ms/op [Average]
  (min, avg, max) = (4.407, 4.451, 4.483), stdev = 0.039
  CI (99.9%): [3.734, 5.167] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.747 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 5.482 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.128 ±(99.9%) 0.006 ms/op
Iteration   1: 4.984 ±(99.9%) 0.005 ms/op
Iteration   2: 4.952 ±(99.9%) 0.005 ms/op
Iteration   3: 4.745 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.894 ±(99.9%) 2.368 ms/op [Average]
  (min, avg, max) = (4.745, 4.894, 4.984), stdev = 0.130
  CI (99.9%): [2.526, 7.261] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.120 ±(99.9%) 0.053 ms/op
# Warmup Iteration   2: 7.178 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 6.483 ±(99.9%) 0.014 ms/op
Iteration   1: 5.940 ±(99.9%) 0.012 ms/op
Iteration   2: 6.139 ±(99.9%) 0.023 ms/op
Iteration   3: 6.174 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.084 ±(99.9%) 2.304 ms/op [Average]
  (min, avg, max) = (5.940, 6.084, 6.174), stdev = 0.126
  CI (99.9%): [3.781, 8.388] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 8.206 ±(99.9%) 0.101 ms/op
# Warmup Iteration   2: 5.136 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.807 ±(99.9%) 0.016 ms/op
Iteration   1: 4.783 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.021 ms/op
                 createUser·p0.50:   4.604 ms/op
                 createUser·p0.90:   6.087 ms/op
                 createUser·p0.95:   6.742 ms/op
                 createUser·p0.99:   9.126 ms/op
                 createUser·p0.999:  12.717 ms/op
                 createUser·p0.9999: 22.653 ms/op
                 createUser·p1.00:   23.593 ms/op

Iteration   2: 4.709 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.137 ms/op
                 createUser·p0.50:   4.538 ms/op
                 createUser·p0.90:   6.021 ms/op
                 createUser·p0.95:   6.586 ms/op
                 createUser·p0.99:   8.864 ms/op
                 createUser·p0.999:  14.094 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.101 ms/op

Iteration   3: 4.696 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   0.936 ms/op
                 createUser·p0.50:   4.547 ms/op
                 createUser·p0.90:   5.980 ms/op
                 createUser·p0.95:   6.636 ms/op
                 createUser·p0.99:   8.962 ms/op
                 createUser·p0.999:  13.575 ms/op
                 createUser·p0.9999: 26.849 ms/op
                 createUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 202901
  mean =      4.729 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4581 
    [ 2.500,  5.000) = 133193 
    [ 5.000,  7.500) = 60008 
    [ 7.500, 10.000) = 4069 
    [10.000, 12.500) = 752 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.936 ms/op
     p(50.0000) =      4.563 ms/op
     p(90.0000) =      6.029 ms/op
     p(95.0000) =      6.652 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     13.322 ms/op
     p(99.9900) =     26.280 ms/op
     p(99.9990) =     27.263 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.263 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 5.065 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.733 ±(99.9%) 0.016 ms/op
Iteration   1: 4.531 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.098 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.784 ms/op
                 existUser·p0.95:   6.570 ms/op
                 existUser·p0.99:   8.618 ms/op
                 existUser·p0.999:  13.637 ms/op
                 existUser·p0.9999: 20.347 ms/op
                 existUser·p1.00:   35.783 ms/op

Iteration   2: 4.572 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.819 ms/op
                 existUser·p0.50:   4.432 ms/op
                 existUser·p0.90:   5.767 ms/op
                 existUser·p0.95:   6.398 ms/op
                 existUser·p0.99:   8.231 ms/op
                 existUser·p0.999:  11.894 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.479 ms/op

Iteration   3: 4.523 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.499 ms/op
                 existUser·p0.50:   4.358 ms/op
                 existUser·p0.90:   5.726 ms/op
                 existUser·p0.95:   6.324 ms/op
                 existUser·p0.99:   8.536 ms/op
                 existUser·p0.999:  14.438 ms/op
                 existUser·p0.9999: 26.474 ms/op
                 existUser·p1.00:   26.903 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 211493
  mean =      4.542 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5583 
    [ 2.500,  5.000) = 152223 
    [ 5.000,  7.500) = 49417 
    [ 7.500, 10.000) = 3534 
    [10.000, 12.500) = 477 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 28 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 33 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.499 ms/op
     p(50.0000) =      4.383 ms/op
     p(90.0000) =      5.759 ms/op
     p(95.0000) =      6.423 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     13.034 ms/op
     p(99.9900) =     25.980 ms/op
     p(99.9990) =     26.895 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 7.699 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 5.183 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 5.001 ±(99.9%) 0.016 ms/op
Iteration   1: 4.891 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.192 ms/op
                 getUser·p0.50:   4.735 ms/op
                 getUser·p0.90:   6.152 ms/op
                 getUser·p0.95:   6.824 ms/op
                 getUser·p0.99:   9.306 ms/op
                 getUser·p0.999:  15.983 ms/op
                 getUser·p0.9999: 17.775 ms/op
                 getUser·p1.00:   18.186 ms/op

Iteration   2: 4.863 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.333 ms/op
                 getUser·p0.50:   4.686 ms/op
                 getUser·p0.90:   6.119 ms/op
                 getUser·p0.95:   6.709 ms/op
                 getUser·p0.99:   8.913 ms/op
                 getUser·p0.999:  13.271 ms/op
                 getUser·p0.9999: 21.027 ms/op
                 getUser·p1.00:   23.364 ms/op

Iteration   3: 4.836 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.467 ms/op
                 getUser·p0.50:   4.702 ms/op
                 getUser·p0.90:   6.103 ms/op
                 getUser·p0.95:   6.627 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  12.220 ms/op
                 getUser·p0.9999: 22.701 ms/op
                 getUser·p1.00:   22.905 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 197391
  mean =      4.863 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3143 
    [ 2.500,  5.000) = 120258 
    [ 5.000,  7.500) = 69189 
    [ 7.500, 10.000) = 3737 
    [10.000, 12.500) = 762 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.467 ms/op
     p(50.0000) =      4.710 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      6.709 ms/op
     p(99.0000) =      8.946 ms/op
     p(99.9000) =     13.586 ms/op
     p(99.9900) =     22.356 ms/op
     p(99.9990) =     23.172 ms/op
     p(99.9999) =     23.364 ms/op
    p(100.0000) =     23.364 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 9.677 ±(99.9%) 0.130 ms/op
# Warmup Iteration   2: 6.759 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.289 ±(99.9%) 0.026 ms/op
Iteration   1: 6.118 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.714 ms/op
                 listUser·p0.50:   5.751 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.290 ms/op
                 listUser·p0.99:   12.665 ms/op
                 listUser·p0.999:  19.292 ms/op
                 listUser·p0.9999: 21.561 ms/op
                 listUser·p1.00:   23.003 ms/op

Iteration   2: 6.154 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   5.792 ms/op
                 listUser·p0.90:   8.200 ms/op
                 listUser·p0.95:   9.175 ms/op
                 listUser·p0.99:   11.796 ms/op
                 listUser·p0.999:  22.446 ms/op
                 listUser·p0.9999: 29.918 ms/op
                 listUser·p1.00:   30.278 ms/op

Iteration   3: 6.175 ±(99.9%) 0.025 ms/op
                 listUser·p0.00:   1.251 ms/op
                 listUser·p0.50:   5.841 ms/op
                 listUser·p0.90:   8.143 ms/op
                 listUser·p0.95:   9.208 ms/op
                 listUser·p0.99:   11.731 ms/op
                 listUser·p0.999:  23.984 ms/op
                 listUser·p0.9999: 31.779 ms/op
                 listUser·p1.00:   32.113 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 156042
  mean =      6.149 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 95 
    [ 2.500,  5.000) = 32224 
    [ 5.000,  7.500) = 99731 
    [ 7.500, 10.000) = 19168 
    [10.000, 12.500) = 3595 
    [12.500, 15.000) = 733 
    [15.000, 17.500) = 210 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 77 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.251 ms/op
     p(50.0000) =      5.792 ms/op
     p(90.0000) =      8.167 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.035 ms/op
     p(99.9000) =     20.906 ms/op
     p(99.9900) =     30.172 ms/op
     p(99.9990) =     31.947 ms/op
     p(99.9999) =     32.113 ms/op
    p(100.0000) =     32.113 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.755 ± 3.507  ops/ms
ClientGrpc.existUser                       thrpt       3   6.891 ± 1.104  ops/ms
ClientGrpc.getUser                         thrpt       3   6.765 ± 1.771  ops/ms
ClientGrpc.listUser                        thrpt       3   5.216 ± 0.600  ops/ms
ClientGrpc.createUser                       avgt       3   4.799 ± 1.198   ms/op
ClientGrpc.existUser                        avgt       3   4.451 ± 0.716   ms/op
ClientGrpc.getUser                          avgt       3   4.894 ± 2.368   ms/op
ClientGrpc.listUser                         avgt       3   6.084 ± 2.304   ms/op
ClientGrpc.createUser                     sample  202901   4.729 ± 0.009   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.936           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.563           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           6.029           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.652           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           8.978           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.322           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          26.280           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.263           ms/op
ClientGrpc.existUser                      sample  211493   4.542 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.499           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.383           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.759           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           6.423           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           8.471           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          13.034           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          25.980           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          35.783           ms/op
ClientGrpc.getUser                        sample  197391   4.863 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.467           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.710           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.119           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.709           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           8.946           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          13.586           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.356           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          23.364           ms/op
ClientGrpc.listUser                       sample  156042   6.149 ± 0.015   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.251           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.792           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           8.167           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           9.224           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          12.035           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.906           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.172           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          32.113           ms/op
