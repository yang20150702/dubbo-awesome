# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 5.142 ops/ms
# Warmup Iteration   2: 9.745 ops/ms
# Warmup Iteration   3: 10.398 ops/ms
Iteration   1: 10.643 ops/ms
Iteration   2: 10.872 ops/ms
Iteration   3: 10.763 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.759 ±(99.9%) 2.091 ops/ms [Average]
  (min, avg, max) = (10.643, 10.759, 10.872), stdev = 0.115
  CI (99.9%): [8.669, 12.850] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 8.206 ops/ms
# Warmup Iteration   2: 10.759 ops/ms
# Warmup Iteration   3: 11.227 ops/ms
Iteration   1: 11.322 ops/ms
Iteration   2: 11.393 ops/ms
Iteration   3: 11.234 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.316 ±(99.9%) 1.447 ops/ms [Average]
  (min, avg, max) = (11.234, 11.316, 11.393), stdev = 0.079
  CI (99.9%): [9.869, 12.764] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 8.623 ops/ms
# Warmup Iteration   2: 10.727 ops/ms
# Warmup Iteration   3: 10.977 ops/ms
Iteration   1: 11.044 ops/ms
Iteration   2: 10.885 ops/ms
Iteration   3: 10.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.947 ±(99.9%) 1.553 ops/ms [Average]
  (min, avg, max) = (10.885, 10.947, 11.044), stdev = 0.085
  CI (99.9%): [9.394, 12.499] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.911 ops/ms
# Warmup Iteration   2: 8.205 ops/ms
# Warmup Iteration   3: 8.501 ops/ms
Iteration   1: 8.468 ops/ms
Iteration   2: 8.482 ops/ms
Iteration   3: 8.715 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.555 ±(99.9%) 2.528 ops/ms [Average]
  (min, avg, max) = (8.468, 8.555, 8.715), stdev = 0.139
  CI (99.9%): [6.027, 11.084] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.039 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.075 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.002 ms/op
Iteration   1: 2.991 ±(99.9%) 0.003 ms/op
Iteration   2: 2.986 ±(99.9%) 0.002 ms/op
Iteration   3: 3.036 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.004 ±(99.9%) 0.505 ms/op [Average]
  (min, avg, max) = (2.986, 3.004, 3.036), stdev = 0.028
  CI (99.9%): [2.499, 3.510] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.567 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.874 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.851 ±(99.9%) 0.003 ms/op
Iteration   1: 2.811 ±(99.9%) 0.004 ms/op
Iteration   2: 2.788 ±(99.9%) 0.003 ms/op
Iteration   3: 2.794 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.798 ±(99.9%) 0.215 ms/op [Average]
  (min, avg, max) = (2.788, 2.798, 2.811), stdev = 0.012
  CI (99.9%): [2.582, 3.013] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.553 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.036 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.959 ±(99.9%) 0.003 ms/op
Iteration   1: 2.925 ±(99.9%) 0.003 ms/op
Iteration   2: 2.928 ±(99.9%) 0.004 ms/op
Iteration   3: 2.989 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.947 ±(99.9%) 0.661 ms/op [Average]
  (min, avg, max) = (2.925, 2.947, 2.989), stdev = 0.036
  CI (99.9%): [2.286, 3.609] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.943 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.816 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.013 ms/op
Iteration   1: 3.758 ±(99.9%) 0.026 ms/op
Iteration   2: 3.744 ±(99.9%) 0.008 ms/op
Iteration   3: 3.705 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.736 ±(99.9%) 0.500 ms/op [Average]
  (min, avg, max) = (3.705, 3.736, 3.758), stdev = 0.027
  CI (99.9%): [3.236, 4.235] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.125 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.146 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 2.948 ±(99.9%) 0.006 ms/op
Iteration   1: 2.953 ±(99.9%) 0.003 ms/op
                 createUser·p0.00:   1.041 ms/op
                 createUser·p0.50:   2.941 ms/op
                 createUser·p0.90:   3.244 ms/op
                 createUser·p0.95:   3.305 ms/op
                 createUser·p0.99:   3.842 ms/op
                 createUser·p0.999:  6.073 ms/op
                 createUser·p0.9999: 11.370 ms/op
                 createUser·p1.00:   11.469 ms/op

Iteration   2: 2.948 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.611 ms/op
                 createUser·p0.50:   2.933 ms/op
                 createUser·p0.90:   3.441 ms/op
                 createUser·p0.95:   3.690 ms/op
                 createUser·p0.99:   4.268 ms/op
                 createUser·p0.999:  6.526 ms/op
                 createUser·p0.9999: 12.736 ms/op
                 createUser·p1.00:   13.140 ms/op

Iteration   3: 3.038 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.623 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.797 ms/op
                 createUser·p0.99:   4.235 ms/op
                 createUser·p0.999:  11.289 ms/op
                 createUser·p0.9999: 23.460 ms/op
                 createUser·p1.00:   23.790 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321973
  mean =      2.979 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 20328 
    [ 2.500,  5.000) = 300705 
    [ 5.000,  7.500) = 600 
    [ 7.500, 10.000) = 54 
    [10.000, 12.500) = 169 
    [12.500, 15.000) = 49 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.957 ms/op
     p(90.0000) =      3.416 ms/op
     p(95.0000) =      3.662 ms/op
     p(99.0000) =      4.145 ms/op
     p(99.9000) =      7.709 ms/op
     p(99.9900) =     21.305 ms/op
     p(99.9990) =     23.691 ms/op
     p(99.9999) =     23.790 ms/op
    p(100.0000) =     23.790 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.687 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.888 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.824 ±(99.9%) 0.006 ms/op
Iteration   1: 2.848 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.611 ms/op
                 existUser·p0.50:   2.843 ms/op
                 existUser·p0.90:   3.252 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  7.084 ms/op
                 existUser·p0.9999: 13.886 ms/op
                 existUser·p1.00:   14.074 ms/op

Iteration   2: 2.829 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.716 ms/op
                 existUser·p0.50:   2.810 ms/op
                 existUser·p0.90:   3.224 ms/op
                 existUser·p0.95:   3.437 ms/op
                 existUser·p0.99:   4.211 ms/op
                 existUser·p0.999:  6.037 ms/op
                 existUser·p0.9999: 18.570 ms/op
                 existUser·p1.00:   20.349 ms/op

Iteration   3: 2.909 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.730 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.547 ms/op
                 existUser·p0.99:   4.288 ms/op
                 existUser·p0.999:  10.942 ms/op
                 existUser·p0.9999: 14.369 ms/op
                 existUser·p1.00:   15.794 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 335461
  mean =      2.862 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 45144 
    [ 2.500,  5.000) = 289393 
    [ 5.000,  7.500) = 602 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 3 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.611 ms/op
     p(50.0000) =      2.839 ms/op
     p(90.0000) =      3.322 ms/op
     p(95.0000) =      3.506 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.324 ms/op
     p(99.9900) =     15.374 ms/op
     p(99.9990) =     19.940 ms/op
     p(99.9999) =     20.349 ms/op
    p(100.0000) =     20.349 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 3.855 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.015 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.961 ±(99.9%) 0.007 ms/op
Iteration   1: 2.930 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.726 ms/op
                 getUser·p0.50:   2.933 ms/op
                 getUser·p0.90:   3.314 ms/op
                 getUser·p0.95:   3.465 ms/op
                 getUser·p0.99:   4.100 ms/op
                 getUser·p0.999:  6.857 ms/op
                 getUser·p0.9999: 14.357 ms/op
                 getUser·p1.00:   15.286 ms/op

Iteration   2: 2.968 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.689 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.498 ms/op
                 getUser·p0.95:   3.633 ms/op
                 getUser·p0.99:   4.145 ms/op
                 getUser·p0.999:  6.368 ms/op
                 getUser·p0.9999: 15.724 ms/op
                 getUser·p1.00:   16.384 ms/op

Iteration   3: 2.905 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   2.912 ms/op
                 getUser·p0.90:   3.465 ms/op
                 getUser·p0.95:   3.662 ms/op
                 getUser·p0.99:   4.293 ms/op
                 getUser·p0.999:  7.957 ms/op
                 getUser·p0.9999: 17.989 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 327168
  mean =      2.934 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2145 
    [ 1.250,  2.500) = 31426 
    [ 2.500,  3.750) = 284294 
    [ 3.750,  5.000) = 8328 
    [ 5.000,  6.250) = 494 
    [ 6.250,  7.500) = 191 
    [ 7.500,  8.750) = 53 
    [ 8.750, 10.000) = 12 
    [10.000, 11.250) = 25 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 20 
    [13.750, 15.000) = 69 
    [15.000, 16.250) = 52 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 31 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      2.933 ms/op
     p(90.0000) =      3.432 ms/op
     p(95.0000) =      3.604 ms/op
     p(99.0000) =      4.194 ms/op
     p(99.9000) =      7.101 ms/op
     p(99.9900) =     17.564 ms/op
     p(99.9990) =     19.366 ms/op
     p(99.9999) =     19.399 ms/op
    p(100.0000) =     19.399 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.164 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.817 ±(99.9%) 0.010 ms/op
Iteration   1: 3.815 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.892 ms/op
                 listUser·p0.50:   3.682 ms/op
                 listUser·p0.90:   4.809 ms/op
                 listUser·p0.95:   5.489 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  12.256 ms/op
                 listUser·p0.9999: 17.125 ms/op
                 listUser·p1.00:   19.825 ms/op

Iteration   2: 3.695 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.757 ms/op
                 listUser·p0.50:   3.576 ms/op
                 listUser·p0.90:   4.588 ms/op
                 listUser·p0.95:   5.366 ms/op
                 listUser·p0.99:   6.496 ms/op
                 listUser·p0.999:  13.681 ms/op
                 listUser·p0.9999: 16.537 ms/op
                 listUser·p1.00:   18.317 ms/op

Iteration   3: 3.827 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.321 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   6.734 ms/op
                 listUser·p0.999:  19.817 ms/op
                 listUser·p0.9999: 25.002 ms/op
                 listUser·p1.00:   25.330 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 254390
  mean =      3.778 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5904 
    [ 2.500,  5.000) = 229503 
    [ 5.000,  7.500) = 17915 
    [ 7.500, 10.000) = 591 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 163 
    [15.000, 17.500) = 92 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      0.757 ms/op
     p(50.0000) =      3.637 ms/op
     p(90.0000) =      4.735 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.603 ms/op
     p(99.9000) =     14.051 ms/op
     p(99.9900) =     23.761 ms/op
     p(99.9990) =     25.243 ms/op
     p(99.9999) =     25.330 ms/op
    p(100.0000) =     25.330 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.759 ± 2.091  ops/ms
ClientGrpc.existUser                       thrpt       3  11.316 ± 1.447  ops/ms
ClientGrpc.getUser                         thrpt       3  10.947 ± 1.553  ops/ms
ClientGrpc.listUser                        thrpt       3   8.555 ± 2.528  ops/ms
ClientGrpc.createUser                       avgt       3   3.004 ± 0.505   ms/op
ClientGrpc.existUser                        avgt       3   2.798 ± 0.215   ms/op
ClientGrpc.getUser                          avgt       3   2.947 ± 0.661   ms/op
ClientGrpc.listUser                         avgt       3   3.736 ± 0.500   ms/op
ClientGrpc.createUser                     sample  321973   2.979 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.611           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.957           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.416           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.662           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.145           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.709           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.305           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.790           ms/op
ClientGrpc.existUser                      sample  335461   2.862 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.611           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.839           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.322           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.324           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.374           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.349           ms/op
ClientGrpc.getUser                        sample  327168   2.934 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.529           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.933           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.604           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.194           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.101           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.564           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.399           ms/op
ClientGrpc.listUser                       sample  254390   3.778 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.757           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.637           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.735           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.603           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.051           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          23.761           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.330           ms/op
