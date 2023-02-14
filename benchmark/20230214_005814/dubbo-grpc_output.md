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
# Warmup Iteration   1: 2.836 ops/ms
# Warmup Iteration   2: 6.785 ops/ms
# Warmup Iteration   3: 7.836 ops/ms
Iteration   1: 7.985 ops/ms
Iteration   2: 7.991 ops/ms
Iteration   3: 7.982 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  7.986 ±(99.9%) 0.079 ops/ms [Average]
  (min, avg, max) = (7.982, 7.986, 7.991), stdev = 0.004
  CI (99.9%): [7.907, 8.065] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 6.205 ops/ms
# Warmup Iteration   2: 8.254 ops/ms
# Warmup Iteration   3: 8.263 ops/ms
Iteration   1: 8.233 ops/ms
Iteration   2: 8.489 ops/ms
Iteration   3: 8.554 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.426 ±(99.9%) 3.092 ops/ms [Average]
  (min, avg, max) = (8.233, 8.426, 8.554), stdev = 0.170
  CI (99.9%): [5.333, 11.518] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.394 ops/ms
# Warmup Iteration   2: 7.642 ops/ms
# Warmup Iteration   3: 7.863 ops/ms
Iteration   1: 7.857 ops/ms
Iteration   2: 7.853 ops/ms
Iteration   3: 7.971 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  7.894 ±(99.9%) 1.215 ops/ms [Average]
  (min, avg, max) = (7.853, 7.894, 7.971), stdev = 0.067
  CI (99.9%): [6.679, 9.109] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.269 ops/ms
# Warmup Iteration   2: 5.960 ops/ms
# Warmup Iteration   3: 6.142 ops/ms
Iteration   1: 6.369 ops/ms
Iteration   2: 6.403 ops/ms
Iteration   3: 6.431 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.401 ±(99.9%) 0.565 ops/ms [Average]
  (min, avg, max) = (6.369, 6.401, 6.431), stdev = 0.031
  CI (99.9%): [5.836, 6.966] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.708 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 4.091 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.920 ±(99.9%) 0.009 ms/op
Iteration   1: 4.172 ±(99.9%) 0.003 ms/op
Iteration   2: 3.952 ±(99.9%) 0.011 ms/op
Iteration   3: 4.109 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.077 ±(99.9%) 2.067 ms/op [Average]
  (min, avg, max) = (3.952, 4.077, 4.172), stdev = 0.113
  CI (99.9%): [2.010, 6.145] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.716 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.938 ±(99.9%) 0.003 ms/op
Iteration   1: 3.857 ±(99.9%) 0.003 ms/op
Iteration   2: 3.791 ±(99.9%) 0.003 ms/op
Iteration   3: 3.880 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.842 ±(99.9%) 0.842 ms/op [Average]
  (min, avg, max) = (3.791, 3.842, 3.880), stdev = 0.046
  CI (99.9%): [3.000, 4.684] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.227 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.133 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.006 ±(99.9%) 0.004 ms/op
Iteration   1: 3.921 ±(99.9%) 0.004 ms/op
Iteration   2: 3.987 ±(99.9%) 0.002 ms/op
Iteration   3: 3.957 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.955 ±(99.9%) 0.599 ms/op [Average]
  (min, avg, max) = (3.921, 3.955, 3.987), stdev = 0.033
  CI (99.9%): [3.356, 4.554] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.408 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 5.280 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.026 ±(99.9%) 0.018 ms/op
Iteration   1: 4.929 ±(99.9%) 0.015 ms/op
Iteration   2: 4.997 ±(99.9%) 0.008 ms/op
Iteration   3: 5.084 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.003 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (4.929, 5.003, 5.084), stdev = 0.078
  CI (99.9%): [3.586, 6.421] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.734 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 4.146 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.012 ms/op
Iteration   1: 4.168 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   0.526 ms/op
                 createUser·p0.50:   4.084 ms/op
                 createUser·p0.90:   5.202 ms/op
                 createUser·p0.95:   5.612 ms/op
                 createUser·p0.99:   7.307 ms/op
                 createUser·p0.999:  12.812 ms/op
                 createUser·p0.9999: 15.024 ms/op
                 createUser·p1.00:   15.303 ms/op

Iteration   2: 3.890 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.009 ms/op
                 createUser·p0.50:   3.809 ms/op
                 createUser·p0.90:   4.661 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   6.414 ms/op
                 createUser·p0.999:  14.202 ms/op
                 createUser·p0.9999: 25.944 ms/op
                 createUser·p1.00:   26.182 ms/op

Iteration   3: 3.926 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.796 ms/op
                 createUser·p0.50:   3.842 ms/op
                 createUser·p0.90:   4.751 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   6.709 ms/op
                 createUser·p0.999:  12.894 ms/op
                 createUser·p0.9999: 20.251 ms/op
                 createUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 240650
  mean =      3.991 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7336 
    [ 2.500,  5.000) = 212619 
    [ 5.000,  7.500) = 19076 
    [ 7.500, 10.000) = 917 
    [10.000, 12.500) = 426 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 10 
    [25.000, 27.500) = 22 

  Percentiles, ms/op:
      p(0.0000) =      0.526 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.907 ms/op
     p(95.0000) =      5.333 ms/op
     p(99.0000) =      6.828 ms/op
     p(99.9000) =     12.998 ms/op
     p(99.9900) =     24.967 ms/op
     p(99.9990) =     26.136 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 5.413 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.203 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.931 ±(99.9%) 0.011 ms/op
Iteration   1: 3.985 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.956 ms/op
                 existUser·p0.50:   3.936 ms/op
                 existUser·p0.90:   4.989 ms/op
                 existUser·p0.95:   5.415 ms/op
                 existUser·p0.99:   6.788 ms/op
                 existUser·p0.999:  13.411 ms/op
                 existUser·p0.9999: 17.724 ms/op
                 existUser·p1.00:   17.957 ms/op

Iteration   2: 3.736 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.005 ms/op
                 existUser·p0.50:   3.727 ms/op
                 existUser·p0.90:   4.702 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   6.349 ms/op
                 existUser·p0.999:  10.781 ms/op
                 existUser·p0.9999: 19.474 ms/op
                 existUser·p1.00:   19.759 ms/op

Iteration   3: 3.809 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   0.928 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.833 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  12.042 ms/op
                 existUser·p0.9999: 21.450 ms/op
                 existUser·p1.00:   21.889 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 249987
  mean =      3.841 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18994 
    [ 2.500,  5.000) = 212357 
    [ 5.000,  7.500) = 17431 
    [ 7.500, 10.000) = 772 
    [10.000, 12.500) = 243 
    [12.500, 15.000) = 60 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.218 ms/op
     p(99.0000) =      6.529 ms/op
     p(99.9000) =     11.371 ms/op
     p(99.9900) =     19.562 ms/op
     p(99.9990) =     21.791 ms/op
     p(99.9999) =     21.889 ms/op
    p(100.0000) =     21.889 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.545 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.917 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.469 ±(99.9%) 0.018 ms/op
Iteration   1: 4.324 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.013 ms/op
                 getUser·p0.50:   4.121 ms/op
                 getUser·p0.90:   5.743 ms/op
                 getUser·p0.95:   6.472 ms/op
                 getUser·p0.99:   8.454 ms/op
                 getUser·p0.999:  14.079 ms/op
                 getUser·p0.9999: 26.628 ms/op
                 getUser·p1.00:   27.492 ms/op

Iteration   2: 4.244 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   0.860 ms/op
                 getUser·p0.50:   4.133 ms/op
                 getUser·p0.90:   5.439 ms/op
                 getUser·p0.95:   6.038 ms/op
                 getUser·p0.99:   7.676 ms/op
                 getUser·p0.999:  11.539 ms/op
                 getUser·p0.9999: 27.966 ms/op
                 getUser·p1.00:   28.508 ms/op

Iteration   3: 3.994 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.015 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.218 ms/op
                 getUser·p0.99:   6.652 ms/op
                 getUser·p0.999:  9.533 ms/op
                 getUser·p0.9999: 30.966 ms/op
                 getUser·p1.00:   30.999 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 229429
  mean =      4.183 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7510 
    [ 2.500,  5.000) = 186443 
    [ 5.000,  7.500) = 32715 
    [ 7.500, 10.000) = 2211 
    [10.000, 12.500) = 335 
    [12.500, 15.000) = 86 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 22 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.860 ms/op
     p(50.0000) =      4.047 ms/op
     p(90.0000) =      5.333 ms/op
     p(95.0000) =      5.964 ms/op
     p(99.0000) =      7.733 ms/op
     p(99.9000) =     12.354 ms/op
     p(99.9900) =     30.054 ms/op
     p(99.9990) =     30.989 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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
# Warmup Iteration   1: 6.046 ±(99.9%) 0.065 ms/op
# Warmup Iteration   2: 5.602 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.940 ±(99.9%) 0.016 ms/op
Iteration   1: 4.946 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.655 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.734 ms/op
                 listUser·p0.95:   7.553 ms/op
                 listUser·p0.99:   9.982 ms/op
                 listUser·p0.999:  16.785 ms/op
                 listUser·p0.9999: 24.871 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   2: 4.773 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.143 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   6.095 ms/op
                 listUser·p0.95:   7.045 ms/op
                 listUser·p0.99:   8.864 ms/op
                 listUser·p0.999:  16.678 ms/op
                 listUser·p0.9999: 21.688 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 5.076 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.374 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.619 ms/op
                 listUser·p0.95:   7.373 ms/op
                 listUser·p0.99:   9.355 ms/op
                 listUser·p0.999:  18.940 ms/op
                 listUser·p0.9999: 21.748 ms/op
                 listUser·p1.00:   21.987 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 194943
  mean =      4.929 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 592 
    [ 2.500,  5.000) = 128329 
    [ 5.000,  7.500) = 57526 
    [ 7.500, 10.000) = 7142 
    [10.000, 12.500) = 724 
    [12.500, 15.000) = 250 
    [15.000, 17.500) = 144 
    [17.500, 20.000) = 143 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      1.143 ms/op
     p(50.0000) =      4.653 ms/op
     p(90.0000) =      6.521 ms/op
     p(95.0000) =      7.348 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     18.483 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     25.107 ms/op
     p(99.9999) =     25.231 ms/op
    p(100.0000) =     25.231 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   7.986 ± 0.079  ops/ms
ClientGrpc.existUser                       thrpt       3   8.426 ± 3.092  ops/ms
ClientGrpc.getUser                         thrpt       3   7.894 ± 1.215  ops/ms
ClientGrpc.listUser                        thrpt       3   6.401 ± 0.565  ops/ms
ClientGrpc.createUser                       avgt       3   4.077 ± 2.067   ms/op
ClientGrpc.existUser                        avgt       3   3.842 ± 0.842   ms/op
ClientGrpc.getUser                          avgt       3   3.955 ± 0.599   ms/op
ClientGrpc.listUser                         avgt       3   5.003 ± 1.418   ms/op
ClientGrpc.createUser                     sample  240650   3.991 ± 0.007   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.526           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.891           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.907           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.333           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.828           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.998           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          24.967           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          26.182           ms/op
ClientGrpc.existUser                      sample  249987   3.841 ± 0.007   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.928           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.822           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.850           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.218           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.529           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.371           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.562           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.889           ms/op
ClientGrpc.getUser                        sample  229429   4.183 ± 0.008   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.860           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.047           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           5.333           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.964           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           7.733           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.354           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          30.054           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          30.999           ms/op
ClientGrpc.listUser                       sample  194943   4.929 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.143           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.653           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.521           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.348           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.355           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          18.483           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          22.446           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.231           ms/op
