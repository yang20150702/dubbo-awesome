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
# Warmup Iteration   1: 3.763 ops/ms
# Warmup Iteration   2: 8.523 ops/ms
# Warmup Iteration   3: 9.881 ops/ms
Iteration   1: 10.423 ops/ms
Iteration   2: 10.504 ops/ms
Iteration   3: 10.446 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.458 ±(99.9%) 0.765 ops/ms [Average]
  (min, avg, max) = (10.423, 10.458, 10.504), stdev = 0.042
  CI (99.9%): [9.693, 11.222] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 7.404 ops/ms
# Warmup Iteration   2: 10.091 ops/ms
# Warmup Iteration   3: 10.839 ops/ms
Iteration   1: 11.015 ops/ms
Iteration   2: 10.923 ops/ms
Iteration   3: 10.876 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.938 ±(99.9%) 1.287 ops/ms [Average]
  (min, avg, max) = (10.876, 10.938, 11.015), stdev = 0.071
  CI (99.9%): [9.651, 12.224] (assumes normal distribution)


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
# Warmup Iteration   1: 7.093 ops/ms
# Warmup Iteration   2: 9.998 ops/ms
# Warmup Iteration   3: 10.283 ops/ms
Iteration   1: 10.461 ops/ms
Iteration   2: 10.515 ops/ms
Iteration   3: 10.399 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.458 ±(99.9%) 1.062 ops/ms [Average]
  (min, avg, max) = (10.399, 10.458, 10.515), stdev = 0.058
  CI (99.9%): [9.396, 11.520] (assumes normal distribution)


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
# Warmup Iteration   1: 4.762 ops/ms
# Warmup Iteration   2: 7.415 ops/ms
# Warmup Iteration   3: 7.802 ops/ms
Iteration   1: 7.915 ops/ms
Iteration   2: 7.731 ops/ms
Iteration   3: 7.759 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.802 ±(99.9%) 1.810 ops/ms [Average]
  (min, avg, max) = (7.731, 7.802, 7.915), stdev = 0.099
  CI (99.9%): [5.992, 9.612] (assumes normal distribution)


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
# Warmup Iteration   1: 4.418 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.224 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.080 ±(99.9%) 0.004 ms/op
Iteration   1: 3.091 ±(99.9%) 0.003 ms/op
Iteration   2: 3.093 ±(99.9%) 0.007 ms/op
Iteration   3: 3.109 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.098 ±(99.9%) 0.182 ms/op [Average]
  (min, avg, max) = (3.091, 3.098, 3.109), stdev = 0.010
  CI (99.9%): [2.916, 3.280] (assumes normal distribution)


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
# Warmup Iteration   1: 4.217 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.029 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.988 ±(99.9%) 0.005 ms/op
Iteration   1: 3.032 ±(99.9%) 0.005 ms/op
Iteration   2: 2.935 ±(99.9%) 0.002 ms/op
Iteration   3: 3.009 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.992 ±(99.9%) 0.924 ms/op [Average]
  (min, avg, max) = (2.935, 2.992, 3.032), stdev = 0.051
  CI (99.9%): [2.068, 3.916] (assumes normal distribution)


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
# Warmup Iteration   1: 4.366 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.240 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.096 ±(99.9%) 0.003 ms/op
Iteration   1: 3.085 ±(99.9%) 0.002 ms/op
Iteration   2: 3.057 ±(99.9%) 0.003 ms/op
Iteration   3: 3.083 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.075 ±(99.9%) 0.286 ms/op [Average]
  (min, avg, max) = (3.057, 3.075, 3.085), stdev = 0.016
  CI (99.9%): [2.789, 3.361] (assumes normal distribution)


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
# Warmup Iteration   1: 5.732 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.245 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.097 ±(99.9%) 0.017 ms/op
Iteration   1: 4.154 ±(99.9%) 0.014 ms/op
Iteration   2: 4.069 ±(99.9%) 0.009 ms/op
Iteration   3: 4.151 ±(99.9%) 0.023 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.124 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (4.069, 4.124, 4.154), stdev = 0.048
  CI (99.9%): [3.240, 5.009] (assumes normal distribution)


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
# Warmup Iteration   1: 4.167 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.210 ±(99.9%) 0.008 ms/op
Iteration   1: 3.196 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.336 ms/op
                 createUser·p0.50:   3.146 ms/op
                 createUser·p0.90:   3.858 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   4.784 ms/op
                 createUser·p0.999:  8.061 ms/op
                 createUser·p0.9999: 23.330 ms/op
                 createUser·p1.00:   23.429 ms/op

Iteration   2: 3.105 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.815 ms/op
                 createUser·p0.50:   3.064 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.936 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  8.782 ms/op
                 createUser·p0.9999: 24.117 ms/op
                 createUser·p1.00:   25.035 ms/op

Iteration   3: 3.180 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.809 ms/op
                 createUser·p0.95:   4.047 ms/op
                 createUser·p0.99:   4.760 ms/op
                 createUser·p0.999:  10.813 ms/op
                 createUser·p0.9999: 27.261 ms/op
                 createUser·p1.00:   27.623 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 303876
  mean =      3.160 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14638 
    [ 2.500,  5.000) = 286762 
    [ 5.000,  7.500) = 1862 
    [ 7.500, 10.000) = 348 
    [10.000, 12.500) = 106 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 60 

  Percentiles, ms/op:
      p(0.0000) =      0.336 ms/op
     p(50.0000) =      3.101 ms/op
     p(90.0000) =      3.777 ms/op
     p(95.0000) =      4.030 ms/op
     p(99.0000) =      4.833 ms/op
     p(99.9000) =      9.339 ms/op
     p(99.9900) =     27.008 ms/op
     p(99.9990) =     27.591 ms/op
     p(99.9999) =     27.623 ms/op
    p(100.0000) =     27.623 ms/op


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
# Warmup Iteration   1: 4.012 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.095 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.962 ±(99.9%) 0.006 ms/op
Iteration   1: 2.932 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.733 ms/op
                 existUser·p0.50:   2.900 ms/op
                 existUser·p0.90:   3.420 ms/op
                 existUser·p0.95:   3.723 ms/op
                 existUser·p0.99:   4.637 ms/op
                 existUser·p0.999:  7.338 ms/op
                 existUser·p0.9999: 14.306 ms/op
                 existUser·p1.00:   16.351 ms/op

Iteration   2: 2.983 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.729 ms/op
                 existUser·p0.50:   2.949 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.650 ms/op
                 existUser·p0.99:   4.702 ms/op
                 existUser·p0.999:  11.190 ms/op
                 existUser·p0.9999: 26.584 ms/op
                 existUser·p1.00:   27.001 ms/op

Iteration   3: 2.904 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.700 ms/op
                 existUser·p0.50:   2.888 ms/op
                 existUser·p0.90:   3.310 ms/op
                 existUser·p0.95:   3.609 ms/op
                 existUser·p0.99:   4.547 ms/op
                 existUser·p0.999:  8.192 ms/op
                 existUser·p0.9999: 39.911 ms/op
                 existUser·p1.00:   40.108 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326412
  mean =      2.939 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 324535 
    [ 5.000, 10.000) = 1627 
    [10.000, 15.000) = 97 
    [15.000, 20.000) = 62 
    [20.000, 25.000) = 27 
    [25.000, 30.000) = 32 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 24 
    [40.000, 45.000) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.700 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.396 ms/op
     p(95.0000) =      3.666 ms/op
     p(99.0000) =      4.628 ms/op
     p(99.9000) =      8.677 ms/op
     p(99.9900) =     30.739 ms/op
     p(99.9990) =     40.108 ms/op
     p(99.9999) =     40.108 ms/op
    p(100.0000) =     40.108 ms/op


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
# Warmup Iteration   1: 4.308 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.244 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.007 ms/op
Iteration   1: 3.112 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.632 ms/op
                 getUser·p0.50:   3.056 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.010 ms/op
                 getUser·p0.99:   4.915 ms/op
                 getUser·p0.999:  10.338 ms/op
                 getUser·p0.9999: 14.883 ms/op
                 getUser·p1.00:   15.335 ms/op

Iteration   2: 3.050 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.829 ms/op
                 getUser·p0.50:   3.019 ms/op
                 getUser·p0.90:   3.543 ms/op
                 getUser·p0.95:   3.838 ms/op
                 getUser·p0.99:   4.964 ms/op
                 getUser·p0.999:  8.339 ms/op
                 getUser·p0.9999: 15.966 ms/op
                 getUser·p1.00:   16.417 ms/op

Iteration   3: 3.098 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.845 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.629 ms/op
                 getUser·p0.95:   3.879 ms/op
                 getUser·p0.99:   4.784 ms/op
                 getUser·p0.999:  10.544 ms/op
                 getUser·p0.9999: 23.746 ms/op
                 getUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311130
  mean =      3.086 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 21375 
    [ 2.500,  5.000) = 287084 
    [ 5.000,  7.500) = 1947 
    [ 7.500, 10.000) = 413 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.632 ms/op
     p(50.0000) =      3.043 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.916 ms/op
     p(99.0000) =      4.899 ms/op
     p(99.9000) =     10.008 ms/op
     p(99.9900) =     22.304 ms/op
     p(99.9990) =     23.921 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 4.783 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.560 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.170 ±(99.9%) 0.012 ms/op
Iteration   1: 4.165 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.559 ms/op
                 listUser·p0.50:   3.973 ms/op
                 listUser·p0.90:   5.341 ms/op
                 listUser·p0.95:   6.152 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  14.290 ms/op
                 listUser·p0.9999: 20.498 ms/op
                 listUser·p1.00:   21.266 ms/op

Iteration   2: 4.138 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   6.005 ms/op
                 listUser·p0.99:   7.538 ms/op
                 listUser·p0.999:  17.662 ms/op
                 listUser·p0.9999: 19.917 ms/op
                 listUser·p1.00:   20.251 ms/op

Iteration   3: 4.166 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.835 ms/op
                 listUser·p0.50:   3.928 ms/op
                 listUser·p0.90:   5.390 ms/op
                 listUser·p0.95:   6.103 ms/op
                 listUser·p0.99:   7.971 ms/op
                 listUser·p0.999:  21.667 ms/op
                 listUser·p0.9999: 28.320 ms/op
                 listUser·p1.00:   28.869 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 230981
  mean =      4.157 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2178 
    [ 2.500,  5.000) = 198237 
    [ 5.000,  7.500) = 27999 
    [ 7.500, 10.000) = 1862 
    [10.000, 12.500) = 229 
    [12.500, 15.000) = 173 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 124 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      0.835 ms/op
     p(50.0000) =      3.953 ms/op
     p(90.0000) =      5.300 ms/op
     p(95.0000) =      6.095 ms/op
     p(99.0000) =      7.627 ms/op
     p(99.9000) =     17.728 ms/op
     p(99.9900) =     26.768 ms/op
     p(99.9990) =     28.770 ms/op
     p(99.9999) =     28.869 ms/op
    p(100.0000) =     28.869 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.458 ± 0.765  ops/ms
ClientGrpc.existUser                       thrpt       3  10.938 ± 1.287  ops/ms
ClientGrpc.getUser                         thrpt       3  10.458 ± 1.062  ops/ms
ClientGrpc.listUser                        thrpt       3   7.802 ± 1.810  ops/ms
ClientGrpc.createUser                       avgt       3   3.098 ± 0.182   ms/op
ClientGrpc.existUser                        avgt       3   2.992 ± 0.924   ms/op
ClientGrpc.getUser                          avgt       3   3.075 ± 0.286   ms/op
ClientGrpc.listUser                         avgt       3   4.124 ± 0.884   ms/op
ClientGrpc.createUser                     sample  303876   3.160 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.336           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.101           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.030           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.833           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.339           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.008           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.623           ms/op
ClientGrpc.existUser                      sample  326412   2.939 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.700           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.396           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.666           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.628           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.677           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          30.739           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          40.108           ms/op
ClientGrpc.getUser                        sample  311130   3.086 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.632           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.043           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.916           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.899           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.008           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.304           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.214           ms/op
ClientGrpc.listUser                       sample  230981   4.157 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.835           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.953           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.300           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.095           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.627           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.728           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.768           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.869           ms/op
