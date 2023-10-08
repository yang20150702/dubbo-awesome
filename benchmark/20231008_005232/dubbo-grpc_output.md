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
# Warmup Iteration   1: 4.614 ops/ms
# Warmup Iteration   2: 9.191 ops/ms
# Warmup Iteration   3: 9.980 ops/ms
Iteration   1: 10.295 ops/ms
Iteration   2: 10.472 ops/ms
Iteration   3: 10.189 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.318 ±(99.9%) 2.610 ops/ms [Average]
  (min, avg, max) = (10.189, 10.318, 10.472), stdev = 0.143
  CI (99.9%): [7.709, 12.928] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:01
# Fork: 1 of 1
# Warmup Iteration   1: 7.370 ops/ms
# Warmup Iteration   2: 10.243 ops/ms
# Warmup Iteration   3: 10.627 ops/ms
Iteration   1: 10.676 ops/ms
Iteration   2: 10.604 ops/ms
Iteration   3: 10.853 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.711 ±(99.9%) 2.330 ops/ms [Average]
  (min, avg, max) = (10.604, 10.711, 10.853), stdev = 0.128
  CI (99.9%): [8.381, 13.042] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:54
# Fork: 1 of 1
# Warmup Iteration   1: 7.395 ops/ms
# Warmup Iteration   2: 9.949 ops/ms
# Warmup Iteration   3: 10.458 ops/ms
Iteration   1: 10.484 ops/ms
Iteration   2: 10.385 ops/ms
Iteration   3: 10.558 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.476 ±(99.9%) 1.582 ops/ms [Average]
  (min, avg, max) = (10.385, 10.476, 10.558), stdev = 0.087
  CI (99.9%): [8.893, 12.058] (assumes normal distribution)


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
# Warmup Iteration   1: 5.731 ops/ms
# Warmup Iteration   2: 8.091 ops/ms
# Warmup Iteration   3: 8.255 ops/ms
Iteration   1: 8.279 ops/ms
Iteration   2: 8.147 ops/ms
Iteration   3: 8.339 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.255 ±(99.9%) 1.792 ops/ms [Average]
  (min, avg, max) = (8.147, 8.255, 8.339), stdev = 0.098
  CI (99.9%): [6.463, 10.047] (assumes normal distribution)


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
# Warmup Iteration   1: 4.268 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.132 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.106 ±(99.9%) 0.003 ms/op
Iteration   1: 3.067 ±(99.9%) 0.003 ms/op
Iteration   2: 3.133 ±(99.9%) 0.005 ms/op
Iteration   3: 3.120 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.107 ±(99.9%) 0.640 ms/op [Average]
  (min, avg, max) = (3.067, 3.107, 3.133), stdev = 0.035
  CI (99.9%): [2.466, 3.747] (assumes normal distribution)


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
# Warmup Iteration   1: 4.115 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.101 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.943 ±(99.9%) 0.004 ms/op
Iteration   1: 2.971 ±(99.9%) 0.004 ms/op
Iteration   2: 2.966 ±(99.9%) 0.004 ms/op
Iteration   3: 3.001 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.979 ±(99.9%) 0.345 ms/op [Average]
  (min, avg, max) = (2.966, 2.979, 3.001), stdev = 0.019
  CI (99.9%): [2.634, 3.325] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 4.098 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.159 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.003 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.107 ±(99.9%) 0.002 ms/op
Iteration   3: 3.104 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.087 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (3.049, 3.087, 3.107), stdev = 0.032
  CI (99.9%): [2.495, 3.678] (assumes normal distribution)


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
# Warmup Iteration   1: 5.059 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.956 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 3.897 ±(99.9%) 0.023 ms/op
Iteration   1: 3.910 ±(99.9%) 0.018 ms/op
Iteration   2: 3.891 ±(99.9%) 0.026 ms/op
Iteration   3: 3.883 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.895 ±(99.9%) 0.249 ms/op [Average]
  (min, avg, max) = (3.883, 3.895, 3.910), stdev = 0.014
  CI (99.9%): [3.646, 4.144] (assumes normal distribution)


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
# Warmup Iteration   1: 3.875 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 3.256 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.124 ±(99.9%) 0.006 ms/op
Iteration   1: 3.073 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.457 ms/op
                 createUser·p0.50:   3.039 ms/op
                 createUser·p0.90:   3.510 ms/op
                 createUser·p0.95:   3.715 ms/op
                 createUser·p0.99:   4.375 ms/op
                 createUser·p0.999:  13.824 ms/op
                 createUser·p0.9999: 23.612 ms/op
                 createUser·p1.00:   23.888 ms/op

Iteration   2: 3.120 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.724 ms/op
                 createUser·p0.50:   3.076 ms/op
                 createUser·p0.90:   3.637 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.563 ms/op
                 createUser·p0.999:  8.733 ms/op
                 createUser·p0.9999: 16.712 ms/op
                 createUser·p1.00:   17.662 ms/op

Iteration   3: 3.084 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.729 ms/op
                 createUser·p0.50:   3.052 ms/op
                 createUser·p0.90:   3.584 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.366 ms/op
                 createUser·p0.999:  9.667 ms/op
                 createUser·p0.9999: 23.384 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 310807
  mean =      3.092 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12105 
    [ 2.500,  5.000) = 296953 
    [ 5.000,  7.500) = 1101 
    [ 7.500, 10.000) = 344 
    [10.000, 12.500) = 26 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 54 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 41 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.457 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.584 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      4.415 ms/op
     p(99.9000) =      9.948 ms/op
     p(99.9900) =     23.396 ms/op
     p(99.9990) =     23.753 ms/op
     p(99.9999) =     23.888 ms/op
    p(100.0000) =     23.888 ms/op


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
# Warmup Iteration   1: 4.079 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.106 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.994 ±(99.9%) 0.006 ms/op
Iteration   1: 2.960 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.718 ms/op
                 existUser·p0.50:   2.941 ms/op
                 existUser·p0.90:   3.518 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   4.317 ms/op
                 existUser·p0.999:  8.961 ms/op
                 existUser·p0.9999: 22.417 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   2: 3.027 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.776 ms/op
                 existUser·p0.50:   2.994 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.781 ms/op
                 existUser·p0.99:   4.563 ms/op
                 existUser·p0.999:  11.226 ms/op
                 existUser·p0.9999: 17.105 ms/op
                 existUser·p1.00:   17.138 ms/op

Iteration   3: 2.976 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.324 ms/op
                 existUser·p0.50:   2.933 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.658 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  13.035 ms/op
                 existUser·p0.9999: 23.822 ms/op
                 existUser·p1.00:   24.314 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 321071
  mean =      2.988 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27139 
    [ 2.500,  5.000) = 292354 
    [ 5.000,  7.500) = 862 
    [ 7.500, 10.000) = 256 
    [10.000, 12.500) = 218 
    [12.500, 15.000) = 132 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.324 ms/op
     p(50.0000) =      2.953 ms/op
     p(90.0000) =      3.510 ms/op
     p(95.0000) =      3.748 ms/op
     p(99.0000) =      4.448 ms/op
     p(99.9000) =     11.092 ms/op
     p(99.9900) =     23.233 ms/op
     p(99.9990) =     24.045 ms/op
     p(99.9999) =     24.314 ms/op
    p(100.0000) =     24.314 ms/op


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
# Warmup Iteration   1: 3.954 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.186 ±(99.9%) 0.008 ms/op
Iteration   1: 3.145 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.593 ms/op
                 getUser·p0.50:   3.092 ms/op
                 getUser·p0.90:   3.731 ms/op
                 getUser·p0.95:   3.903 ms/op
                 getUser·p0.99:   4.841 ms/op
                 getUser·p0.999:  9.543 ms/op
                 getUser·p0.9999: 17.525 ms/op
                 getUser·p1.00:   18.448 ms/op

Iteration   2: 3.055 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.765 ms/op
                 getUser·p0.50:   3.039 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.432 ms/op
                 getUser·p0.999:  8.325 ms/op
                 getUser·p0.9999: 18.894 ms/op
                 getUser·p1.00:   20.283 ms/op

Iteration   3: 3.087 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.575 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.678 ms/op
                 getUser·p0.99:   4.071 ms/op
                 getUser·p0.999:  7.515 ms/op
                 getUser·p0.9999: 24.094 ms/op
                 getUser·p1.00:   24.543 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310173
  mean =      3.095 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13772 
    [ 2.500,  5.000) = 294670 
    [ 5.000,  7.500) = 1272 
    [ 7.500, 10.000) = 220 
    [10.000, 12.500) = 34 
    [12.500, 15.000) = 20 
    [15.000, 17.500) = 60 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.575 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.617 ms/op
     p(95.0000) =      3.801 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.582 ms/op
     p(99.9900) =     22.151 ms/op
     p(99.9990) =     24.412 ms/op
     p(99.9999) =     24.543 ms/op
    p(100.0000) =     24.543 ms/op


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
# Warmup Iteration   1: 4.462 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 4.114 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.782 ±(99.9%) 0.010 ms/op
Iteration   1: 3.926 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.356 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.709 ms/op
                 listUser·p0.999:  13.631 ms/op
                 listUser·p0.9999: 15.740 ms/op
                 listUser·p1.00:   16.171 ms/op

Iteration   2: 3.904 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.149 ms/op
                 listUser·p0.50:   3.777 ms/op
                 listUser·p0.90:   4.686 ms/op
                 listUser·p0.95:   5.685 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  14.799 ms/op
                 listUser·p0.9999: 18.490 ms/op
                 listUser·p1.00:   19.464 ms/op

Iteration   3: 3.922 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.108 ms/op
                 listUser·p0.50:   3.817 ms/op
                 listUser·p0.90:   4.399 ms/op
                 listUser·p0.95:   5.562 ms/op
                 listUser·p0.99:   6.791 ms/op
                 listUser·p0.999:  13.746 ms/op
                 listUser·p0.9999: 19.908 ms/op
                 listUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 245023
  mean =      3.917 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4413 
    [ 2.500,  5.000) = 222580 
    [ 5.000,  7.500) = 16818 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 180 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 113 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.356 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.579 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      6.685 ms/op
     p(99.9000) =     14.238 ms/op
     p(99.9900) =     19.235 ms/op
     p(99.9990) =     20.188 ms/op
     p(99.9999) =     20.316 ms/op
    p(100.0000) =     20.316 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.318 ± 2.610  ops/ms
ClientGrpc.existUser                       thrpt       3  10.711 ± 2.330  ops/ms
ClientGrpc.getUser                         thrpt       3  10.476 ± 1.582  ops/ms
ClientGrpc.listUser                        thrpt       3   8.255 ± 1.792  ops/ms
ClientGrpc.createUser                       avgt       3   3.107 ± 0.640   ms/op
ClientGrpc.existUser                        avgt       3   2.979 ± 0.345   ms/op
ClientGrpc.getUser                          avgt       3   3.087 ± 0.592   ms/op
ClientGrpc.listUser                         avgt       3   3.895 ± 0.249   ms/op
ClientGrpc.createUser                     sample  310807   3.092 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.457           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.056           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.584           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.764           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.415           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.948           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.396           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.888           ms/op
ClientGrpc.existUser                      sample  321071   2.988 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.324           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.953           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.510           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.748           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.448           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.092           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.233           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          24.314           ms/op
ClientGrpc.getUser                        sample  310173   3.095 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.575           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.060           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.617           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.801           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.465           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           8.582           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          22.151           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.543           ms/op
ClientGrpc.listUser                       sample  245023   3.917 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.356           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.805           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.579           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.579           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.685           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.238           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          19.235           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          20.316           ms/op
