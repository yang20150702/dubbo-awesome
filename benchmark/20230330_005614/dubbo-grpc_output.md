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
# Warmup Iteration   1: 3.792 ops/ms
# Warmup Iteration   2: 8.983 ops/ms
# Warmup Iteration   3: 9.903 ops/ms
Iteration   1: 10.586 ops/ms
Iteration   2: 10.722 ops/ms
Iteration   3: 10.385 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.564 ±(99.9%) 3.088 ops/ms [Average]
  (min, avg, max) = (10.385, 10.564, 10.722), stdev = 0.169
  CI (99.9%): [7.476, 13.652] (assumes normal distribution)


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
# Warmup Iteration   1: 7.279 ops/ms
# Warmup Iteration   2: 10.477 ops/ms
# Warmup Iteration   3: 10.854 ops/ms
Iteration   1: 10.926 ops/ms
Iteration   2: 10.837 ops/ms
Iteration   3: 11.119 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.961 ±(99.9%) 2.634 ops/ms [Average]
  (min, avg, max) = (10.837, 10.961, 11.119), stdev = 0.144
  CI (99.9%): [8.327, 13.594] (assumes normal distribution)


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
# Warmup Iteration   1: 6.519 ops/ms
# Warmup Iteration   2: 10.127 ops/ms
# Warmup Iteration   3: 10.409 ops/ms
Iteration   1: 10.672 ops/ms
Iteration   2: 10.589 ops/ms
Iteration   3: 10.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.632 ±(99.9%) 0.763 ops/ms [Average]
  (min, avg, max) = (10.589, 10.632, 10.672), stdev = 0.042
  CI (99.9%): [9.869, 11.394] (assumes normal distribution)


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
# Warmup Iteration   1: 6.071 ops/ms
# Warmup Iteration   2: 7.579 ops/ms
# Warmup Iteration   3: 8.012 ops/ms
Iteration   1: 8.078 ops/ms
Iteration   2: 8.150 ops/ms
Iteration   3: 8.266 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.165 ±(99.9%) 1.725 ops/ms [Average]
  (min, avg, max) = (8.078, 8.165, 8.266), stdev = 0.095
  CI (99.9%): [6.439, 9.890] (assumes normal distribution)


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
# Warmup Iteration   1: 4.247 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.193 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.047 ±(99.9%) 0.003 ms/op
Iteration   1: 3.018 ±(99.9%) 0.008 ms/op
Iteration   2: 3.032 ±(99.9%) 0.014 ms/op
Iteration   3: 3.058 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.036 ±(99.9%) 0.365 ms/op [Average]
  (min, avg, max) = (3.018, 3.036, 3.058), stdev = 0.020
  CI (99.9%): [2.671, 3.401] (assumes normal distribution)


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
# Warmup Iteration   1: 4.121 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.002 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.912 ±(99.9%) 0.002 ms/op
Iteration   1: 2.916 ±(99.9%) 0.003 ms/op
Iteration   2: 2.873 ±(99.9%) 0.003 ms/op
Iteration   3: 2.882 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.890 ±(99.9%) 0.417 ms/op [Average]
  (min, avg, max) = (2.873, 2.890, 2.916), stdev = 0.023
  CI (99.9%): [2.474, 3.307] (assumes normal distribution)


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
# Warmup Iteration   1: 4.246 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.017 ±(99.9%) 0.003 ms/op
Iteration   1: 3.009 ±(99.9%) 0.001 ms/op
Iteration   2: 2.971 ±(99.9%) 0.004 ms/op
Iteration   3: 2.995 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.991 ±(99.9%) 0.351 ms/op [Average]
  (min, avg, max) = (2.971, 2.991, 3.009), stdev = 0.019
  CI (99.9%): [2.640, 3.343] (assumes normal distribution)


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
# Warmup Iteration   1: 5.307 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 4.076 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.033 ±(99.9%) 0.012 ms/op
Iteration   1: 4.012 ±(99.9%) 0.008 ms/op
Iteration   2: 4.005 ±(99.9%) 0.018 ms/op
Iteration   3: 3.906 ±(99.9%) 0.025 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.974 ±(99.9%) 1.080 ms/op [Average]
  (min, avg, max) = (3.906, 3.974, 4.012), stdev = 0.059
  CI (99.9%): [2.894, 5.055] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 4.360 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.195 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.034 ±(99.9%) 0.006 ms/op
Iteration   1: 3.047 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.703 ms/op
                 createUser·p0.50:   3.006 ms/op
                 createUser·p0.90:   3.559 ms/op
                 createUser·p0.95:   3.826 ms/op
                 createUser·p0.99:   4.555 ms/op
                 createUser·p0.999:  7.324 ms/op
                 createUser·p0.9999: 13.116 ms/op
                 createUser·p1.00:   13.484 ms/op

Iteration   2: 3.037 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.723 ms/op
                 createUser·p0.50:   2.998 ms/op
                 createUser·p0.90:   3.600 ms/op
                 createUser·p0.95:   3.858 ms/op
                 createUser·p0.99:   4.776 ms/op
                 createUser·p0.999:  7.663 ms/op
                 createUser·p0.9999: 16.310 ms/op
                 createUser·p1.00:   17.367 ms/op

Iteration   3: 2.964 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.665 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.359 ms/op
                 createUser·p0.95:   3.490 ms/op
                 createUser·p0.99:   4.131 ms/op
                 createUser·p0.999:  12.173 ms/op
                 createUser·p0.9999: 21.004 ms/op
                 createUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 318227
  mean =      3.015 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25138 
    [ 2.500,  5.000) = 291455 
    [ 5.000,  7.500) = 1267 
    [ 7.500, 10.000) = 95 
    [10.000, 12.500) = 87 
    [12.500, 15.000) = 81 
    [15.000, 17.500) = 72 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.665 ms/op
     p(50.0000) =      2.982 ms/op
     p(90.0000) =      3.494 ms/op
     p(95.0000) =      3.731 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      8.184 ms/op
     p(99.9900) =     18.954 ms/op
     p(99.9990) =     21.260 ms/op
     p(99.9999) =     21.365 ms/op
    p(100.0000) =     21.365 ms/op


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
# Warmup Iteration   1: 3.925 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 2.975 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.889 ±(99.9%) 0.006 ms/op
Iteration   1: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.755 ms/op
                 existUser·p0.50:   2.867 ms/op
                 existUser·p0.90:   3.416 ms/op
                 existUser·p0.95:   3.568 ms/op
                 existUser·p0.99:   4.301 ms/op
                 existUser·p0.999:  8.871 ms/op
                 existUser·p0.9999: 12.567 ms/op
                 existUser·p1.00:   12.894 ms/op

Iteration   2: 2.893 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.623 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.604 ms/op
                 existUser·p0.99:   4.063 ms/op
                 existUser·p0.999:  5.410 ms/op
                 existUser·p0.9999: 14.073 ms/op
                 existUser·p1.00:   14.303 ms/op

Iteration   3: 2.864 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.873 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.326 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.293 ms/op
                 existUser·p0.999:  8.013 ms/op
                 existUser·p0.9999: 16.149 ms/op
                 existUser·p1.00:   17.367 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 332808
  mean =      2.883 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2611 
    [ 1.250,  2.500) = 45580 
    [ 2.500,  3.750) = 275976 
    [ 3.750,  5.000) = 7463 
    [ 5.000,  6.250) = 686 
    [ 6.250,  7.500) = 196 
    [ 7.500,  8.750) = 52 
    [ 8.750, 10.000) = 67 
    [10.000, 11.250) = 17 
    [11.250, 12.500) = 50 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 50 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 7 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.871 ms/op
     p(90.0000) =      3.400 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.202 ms/op
     p(99.9000) =      7.078 ms/op
     p(99.9900) =     15.696 ms/op
     p(99.9990) =     16.995 ms/op
     p(99.9999) =     17.367 ms/op
    p(100.0000) =     17.367 ms/op


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
# Warmup Iteration   1: 4.116 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.203 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.074 ±(99.9%) 0.006 ms/op
Iteration   1: 3.015 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.770 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.469 ms/op
                 getUser·p0.95:   3.703 ms/op
                 getUser·p0.99:   4.563 ms/op
                 getUser·p0.999:  7.755 ms/op
                 getUser·p0.9999: 13.196 ms/op
                 getUser·p1.00:   13.664 ms/op

Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.807 ms/op
                 getUser·p0.50:   3.011 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.756 ms/op
                 getUser·p0.99:   4.596 ms/op
                 getUser·p0.999:  6.873 ms/op
                 getUser·p0.9999: 16.204 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   3: 2.989 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.764 ms/op
                 getUser·p0.50:   2.966 ms/op
                 getUser·p0.90:   3.383 ms/op
                 getUser·p0.95:   3.572 ms/op
                 getUser·p0.99:   4.219 ms/op
                 getUser·p0.999:  7.069 ms/op
                 getUser·p0.9999: 16.482 ms/op
                 getUser·p1.00:   17.662 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 318099
  mean =      3.015 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 554 
    [ 1.250,  2.500) = 19758 
    [ 2.500,  3.750) = 284253 
    [ 3.750,  5.000) = 11836 
    [ 5.000,  6.250) = 1094 
    [ 6.250,  7.500) = 319 
    [ 7.500,  8.750) = 47 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 48 
    [11.250, 12.500) = 10 
    [12.500, 13.750) = 42 
    [13.750, 15.000) = 16 
    [15.000, 16.250) = 67 
    [16.250, 17.500) = 27 
    [17.500, 18.750) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.764 ms/op
     p(50.0000) =      2.986 ms/op
     p(90.0000) =      3.461 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.489 ms/op
     p(99.9000) =      7.298 ms/op
     p(99.9900) =     16.226 ms/op
     p(99.9990) =     17.650 ms/op
     p(99.9999) =     17.695 ms/op
    p(100.0000) =     17.695 ms/op


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
# Warmup Iteration   1: 4.877 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 4.340 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.013 ±(99.9%) 0.011 ms/op
Iteration   1: 4.004 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.309 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.849 ms/op
                 listUser·p0.99:   7.012 ms/op
                 listUser·p0.999:  13.877 ms/op
                 listUser·p0.9999: 16.777 ms/op
                 listUser·p1.00:   17.400 ms/op

Iteration   2: 4.009 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.243 ms/op
                 listUser·p0.50:   3.813 ms/op
                 listUser·p0.90:   5.112 ms/op
                 listUser·p0.95:   5.800 ms/op
                 listUser·p0.99:   6.963 ms/op
                 listUser·p0.999:  15.729 ms/op
                 listUser·p0.9999: 21.136 ms/op
                 listUser·p1.00:   21.529 ms/op

Iteration   3: 3.951 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.225 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.784 ms/op
                 listUser·p0.95:   5.579 ms/op
                 listUser·p0.99:   6.922 ms/op
                 listUser·p0.999:  18.624 ms/op
                 listUser·p0.9999: 24.838 ms/op
                 listUser·p1.00:   25.592 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 240827
  mean =      3.988 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2629 
    [ 2.500,  5.000) = 214646 
    [ 5.000,  7.500) = 22342 
    [ 7.500, 10.000) = 812 
    [10.000, 12.500) = 32 
    [12.500, 15.000) = 123 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 33 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.981 ms/op
     p(95.0000) =      5.759 ms/op
     p(99.0000) =      6.963 ms/op
     p(99.9000) =     15.090 ms/op
     p(99.9900) =     24.147 ms/op
     p(99.9990) =     25.446 ms/op
     p(99.9999) =     25.592 ms/op
    p(100.0000) =     25.592 ms/op


# Run complete. Total time: 00:13:05

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.564 ± 3.088  ops/ms
ClientGrpc.existUser                       thrpt       3  10.961 ± 2.634  ops/ms
ClientGrpc.getUser                         thrpt       3  10.632 ± 0.763  ops/ms
ClientGrpc.listUser                        thrpt       3   8.165 ± 1.725  ops/ms
ClientGrpc.createUser                       avgt       3   3.036 ± 0.365   ms/op
ClientGrpc.existUser                        avgt       3   2.890 ± 0.417   ms/op
ClientGrpc.getUser                          avgt       3   2.991 ± 0.351   ms/op
ClientGrpc.listUser                         avgt       3   3.974 ± 1.080   ms/op
ClientGrpc.createUser                     sample  318227   3.015 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.665           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.982           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.494           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.731           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           8.184           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          18.954           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.365           ms/op
ClientGrpc.existUser                      sample  332808   2.883 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.623           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.871           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.400           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.202           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.078           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          15.696           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          17.367           ms/op
ClientGrpc.getUser                        sample  318099   3.015 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.764           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.986           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.461           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.690           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.489           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.298           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.226           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.695           ms/op
ClientGrpc.listUser                       sample  240827   3.988 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.225           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.822           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.981           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.759           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.963           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.090           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.147           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.592           ms/op
