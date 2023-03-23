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
# Warmup Iteration   1: 4.707 ops/ms
# Warmup Iteration   2: 9.328 ops/ms
# Warmup Iteration   3: 10.162 ops/ms
Iteration   1: 10.594 ops/ms
Iteration   2: 10.645 ops/ms
Iteration   3: 10.641 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.626 ±(99.9%) 0.513 ops/ms [Average]
  (min, avg, max) = (10.594, 10.626, 10.645), stdev = 0.028
  CI (99.9%): [10.113, 11.140] (assumes normal distribution)


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
# Warmup Iteration   1: 7.728 ops/ms
# Warmup Iteration   2: 10.697 ops/ms
# Warmup Iteration   3: 11.023 ops/ms
Iteration   1: 11.198 ops/ms
Iteration   2: 11.322 ops/ms
Iteration   3: 11.150 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.223 ±(99.9%) 1.624 ops/ms [Average]
  (min, avg, max) = (11.150, 11.223, 11.322), stdev = 0.089
  CI (99.9%): [9.599, 12.847] (assumes normal distribution)


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
# Warmup Iteration   1: 7.461 ops/ms
# Warmup Iteration   2: 10.374 ops/ms
# Warmup Iteration   3: 10.543 ops/ms
Iteration   1: 10.498 ops/ms
Iteration   2: 10.536 ops/ms
Iteration   3: 10.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.511 ±(99.9%) 0.396 ops/ms [Average]
  (min, avg, max) = (10.498, 10.511, 10.536), stdev = 0.022
  CI (99.9%): [10.115, 10.907] (assumes normal distribution)


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
# Warmup Iteration   1: 6.011 ops/ms
# Warmup Iteration   2: 7.706 ops/ms
# Warmup Iteration   3: 7.832 ops/ms
Iteration   1: 8.227 ops/ms
Iteration   2: 8.247 ops/ms
Iteration   3: 8.045 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.173 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (8.045, 8.173, 8.247), stdev = 0.111
  CI (99.9%): [6.145, 10.201] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 4.313 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.212 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.056 ±(99.9%) 0.005 ms/op
Iteration   2: 3.030 ±(99.9%) 0.002 ms/op
Iteration   3: 3.012 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.033 ±(99.9%) 0.401 ms/op [Average]
  (min, avg, max) = (3.012, 3.033, 3.056), stdev = 0.022
  CI (99.9%): [2.632, 3.434] (assumes normal distribution)


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
# Warmup Iteration   1: 3.806 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.019 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 2.905 ±(99.9%) 0.003 ms/op
Iteration   1: 2.888 ±(99.9%) 0.003 ms/op
Iteration   2: 2.916 ±(99.9%) 0.003 ms/op
Iteration   3: 2.798 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.867 ±(99.9%) 1.125 ms/op [Average]
  (min, avg, max) = (2.798, 2.867, 2.916), stdev = 0.062
  CI (99.9%): [1.742, 3.992] (assumes normal distribution)


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
# Warmup Iteration   1: 4.054 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.139 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.004 ms/op
Iteration   1: 3.040 ±(99.9%) 0.003 ms/op
Iteration   2: 3.036 ±(99.9%) 0.003 ms/op
Iteration   3: 3.060 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.045 ±(99.9%) 0.232 ms/op [Average]
  (min, avg, max) = (3.036, 3.045, 3.060), stdev = 0.013
  CI (99.9%): [2.814, 3.277] (assumes normal distribution)


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
# Warmup Iteration   1: 5.452 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.298 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.979 ±(99.9%) 0.014 ms/op
Iteration   1: 3.797 ±(99.9%) 0.020 ms/op
Iteration   2: 3.872 ±(99.9%) 0.008 ms/op
Iteration   3: 3.899 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.856 ±(99.9%) 0.966 ms/op [Average]
  (min, avg, max) = (3.797, 3.856, 3.899), stdev = 0.053
  CI (99.9%): [2.891, 4.822] (assumes normal distribution)


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
# Warmup Iteration   1: 4.181 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.199 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.086 ±(99.9%) 0.006 ms/op
Iteration   1: 3.058 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.768 ms/op
                 createUser·p0.99:   4.637 ms/op
                 createUser·p0.999:  7.947 ms/op
                 createUser·p0.9999: 12.362 ms/op
                 createUser·p1.00:   12.534 ms/op

Iteration   2: 3.006 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.802 ms/op
                 createUser·p0.50:   2.982 ms/op
                 createUser·p0.90:   3.473 ms/op
                 createUser·p0.95:   3.740 ms/op
                 createUser·p0.99:   4.719 ms/op
                 createUser·p0.999:  11.691 ms/op
                 createUser·p0.9999: 21.332 ms/op
                 createUser·p1.00:   21.922 ms/op

Iteration   3: 3.000 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.718 ms/op
                 createUser·p0.50:   2.990 ms/op
                 createUser·p0.90:   3.514 ms/op
                 createUser·p0.95:   3.707 ms/op
                 createUser·p0.99:   4.522 ms/op
                 createUser·p0.999:  6.619 ms/op
                 createUser·p0.9999: 16.750 ms/op
                 createUser·p1.00:   17.007 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 317638
  mean =      3.021 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 26951 
    [ 2.500,  5.000) = 289070 
    [ 5.000,  7.500) = 1299 
    [ 7.500, 10.000) = 61 
    [10.000, 12.500) = 125 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.718 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.645 ms/op
     p(99.9000) =      7.504 ms/op
     p(99.9900) =     20.602 ms/op
     p(99.9990) =     21.714 ms/op
     p(99.9999) =     21.922 ms/op
    p(100.0000) =     21.922 ms/op


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
# Warmup Iteration   1: 4.111 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.054 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.922 ±(99.9%) 0.005 ms/op
Iteration   1: 2.856 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.803 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.342 ms/op
                 existUser·p0.999:  5.953 ms/op
                 existUser·p0.9999: 16.774 ms/op
                 existUser·p1.00:   17.990 ms/op

Iteration   2: 2.940 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.852 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.162 ms/op
                 existUser·p0.999:  7.275 ms/op
                 existUser·p0.9999: 16.453 ms/op
                 existUser·p1.00:   16.876 ms/op

Iteration   3: 2.916 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.800 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   4.178 ms/op
                 existUser·p0.999:  11.364 ms/op
                 existUser·p0.9999: 21.496 ms/op
                 existUser·p1.00:   21.791 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 330704
  mean =      2.904 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 40245 
    [ 2.500,  5.000) = 289565 
    [ 5.000,  7.500) = 593 
    [ 7.500, 10.000) = 46 
    [10.000, 12.500) = 127 
    [12.500, 15.000) = 27 
    [15.000, 17.500) = 66 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 22 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.800 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.351 ms/op
     p(95.0000) =      3.543 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.277 ms/op
     p(99.9900) =     17.985 ms/op
     p(99.9990) =     21.715 ms/op
     p(99.9999) =     21.791 ms/op
    p(100.0000) =     21.791 ms/op


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
# Warmup Iteration   1: 4.092 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.144 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.065 ±(99.9%) 0.006 ms/op
Iteration   1: 3.052 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.903 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.531 ms/op
                 getUser·p0.95:   3.654 ms/op
                 getUser·p0.99:   4.166 ms/op
                 getUser·p0.999:  6.570 ms/op
                 getUser·p0.9999: 21.087 ms/op
                 getUser·p1.00:   21.594 ms/op

Iteration   2: 2.992 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.836 ms/op
                 getUser·p0.50:   2.986 ms/op
                 getUser·p0.90:   3.494 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.211 ms/op
                 getUser·p0.999:  7.160 ms/op
                 getUser·p0.9999: 13.358 ms/op
                 getUser·p1.00:   14.369 ms/op

Iteration   3: 3.004 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   2.978 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.609 ms/op
                 getUser·p0.99:   4.473 ms/op
                 getUser·p0.999:  7.004 ms/op
                 getUser·p0.9999: 28.028 ms/op
                 getUser·p1.00:   29.196 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318278
  mean =      3.016 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19094 
    [ 2.500,  5.000) = 298048 
    [ 5.000,  7.500) = 888 
    [ 7.500, 10.000) = 55 
    [10.000, 12.500) = 1 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.482 ms/op
     p(95.0000) =      3.658 ms/op
     p(99.0000) =      4.243 ms/op
     p(99.9000) =      6.914 ms/op
     p(99.9900) =     27.432 ms/op
     p(99.9990) =     29.092 ms/op
     p(99.9999) =     29.196 ms/op
    p(100.0000) =     29.196 ms/op


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
# Warmup Iteration   1: 5.400 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.986 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.010 ms/op
Iteration   1: 3.912 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.352 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.973 ms/op
                 listUser·p0.95:   5.530 ms/op
                 listUser·p0.99:   6.726 ms/op
                 listUser·p0.999:  13.222 ms/op
                 listUser·p0.9999: 15.065 ms/op
                 listUser·p1.00:   15.745 ms/op

Iteration   2: 3.886 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.075 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.734 ms/op
                 listUser·p0.99:   6.840 ms/op
                 listUser·p0.999:  14.991 ms/op
                 listUser·p0.9999: 20.406 ms/op
                 listUser·p1.00:   20.808 ms/op

Iteration   3: 3.894 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.891 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.563 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.693 ms/op
                 listUser·p0.999:  14.508 ms/op
                 listUser·p0.9999: 16.433 ms/op
                 listUser·p1.00:   17.531 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246350
  mean =      3.897 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2986 
    [ 2.500,  5.000) = 222586 
    [ 5.000,  7.500) = 19722 
    [ 7.500, 10.000) = 559 
    [10.000, 12.500) = 105 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 102 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.891 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.562 ms/op
     p(99.0000) =      6.767 ms/op
     p(99.9000) =     14.134 ms/op
     p(99.9900) =     18.800 ms/op
     p(99.9990) =     20.583 ms/op
     p(99.9999) =     20.808 ms/op
    p(100.0000) =     20.808 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.626 ± 0.513  ops/ms
ClientGrpc.existUser                       thrpt       3  11.223 ± 1.624  ops/ms
ClientGrpc.getUser                         thrpt       3  10.511 ± 0.396  ops/ms
ClientGrpc.listUser                        thrpt       3   8.173 ± 2.028  ops/ms
ClientGrpc.createUser                       avgt       3   3.033 ± 0.401   ms/op
ClientGrpc.existUser                        avgt       3   2.867 ± 1.125   ms/op
ClientGrpc.getUser                          avgt       3   3.045 ± 0.232   ms/op
ClientGrpc.listUser                         avgt       3   3.856 ± 0.966   ms/op
ClientGrpc.createUser                     sample  317638   3.021 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.718           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.998           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.535           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.740           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.645           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.504           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.602           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.922           ms/op
ClientGrpc.existUser                      sample  330704   2.904 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.800           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.351           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.543           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.277           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.985           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.791           ms/op
ClientGrpc.getUser                        sample  318278   3.016 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.994           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.482           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.658           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.243           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.914           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.432           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.196           ms/op
ClientGrpc.listUser                       sample  246350   3.897 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.891           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.748           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.841           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.562           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.767           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.134           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          18.800           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.808           ms/op
