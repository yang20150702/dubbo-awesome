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
# Warmup Iteration   1: 4.438 ops/ms
# Warmup Iteration   2: 9.138 ops/ms
# Warmup Iteration   3: 9.764 ops/ms
Iteration   1: 10.051 ops/ms
Iteration   2: 10.438 ops/ms
Iteration   3: 10.411 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.300 ±(99.9%) 3.940 ops/ms [Average]
  (min, avg, max) = (10.051, 10.300, 10.438), stdev = 0.216
  CI (99.9%): [6.359, 14.240] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:59
# Fork: 1 of 1
# Warmup Iteration   1: 8.112 ops/ms
# Warmup Iteration   2: 10.452 ops/ms
# Warmup Iteration   3: 10.602 ops/ms
Iteration   1: 11.451 ops/ms
Iteration   2: 10.764 ops/ms
Iteration   3: 10.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.997 ±(99.9%) 7.183 ops/ms [Average]
  (min, avg, max) = (10.764, 10.997, 11.451), stdev = 0.394
  CI (99.9%): [3.814, 18.180] (assumes normal distribution)


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
# Warmup Iteration   1: 6.958 ops/ms
# Warmup Iteration   2: 10.068 ops/ms
# Warmup Iteration   3: 10.246 ops/ms
Iteration   1: 10.486 ops/ms
Iteration   2: 10.203 ops/ms
Iteration   3: 10.437 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.375 ±(99.9%) 2.761 ops/ms [Average]
  (min, avg, max) = (10.203, 10.375, 10.486), stdev = 0.151
  CI (99.9%): [7.614, 13.137] (assumes normal distribution)


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
# Warmup Iteration   1: 6.006 ops/ms
# Warmup Iteration   2: 8.083 ops/ms
# Warmup Iteration   3: 8.211 ops/ms
Iteration   1: 8.256 ops/ms
Iteration   2: 8.217 ops/ms
Iteration   3: 8.352 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.275 ±(99.9%) 1.260 ops/ms [Average]
  (min, avg, max) = (8.217, 8.275, 8.352), stdev = 0.069
  CI (99.9%): [7.015, 9.535] (assumes normal distribution)


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
# Warmup Iteration   1: 4.278 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.161 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.033 ±(99.9%) 0.002 ms/op
Iteration   1: 3.051 ±(99.9%) 0.006 ms/op
Iteration   2: 3.073 ±(99.9%) 0.001 ms/op
Iteration   3: 3.062 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.062 ±(99.9%) 0.199 ms/op [Average]
  (min, avg, max) = (3.051, 3.062, 3.073), stdev = 0.011
  CI (99.9%): [2.863, 3.261] (assumes normal distribution)


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
# Warmup Iteration   1: 3.866 ±(99.9%) 0.009 ms/op
# Warmup Iteration   2: 2.988 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.977 ±(99.9%) 0.006 ms/op
Iteration   1: 2.914 ±(99.9%) 0.004 ms/op
Iteration   2: 2.897 ±(99.9%) 0.004 ms/op
Iteration   3: 2.888 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.900 ±(99.9%) 0.242 ms/op [Average]
  (min, avg, max) = (2.888, 2.900, 2.914), stdev = 0.013
  CI (99.9%): [2.658, 3.142] (assumes normal distribution)


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
# Warmup Iteration   1: 3.853 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.094 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.035 ±(99.9%) 0.004 ms/op
Iteration   1: 3.049 ±(99.9%) 0.003 ms/op
Iteration   2: 3.109 ±(99.9%) 0.003 ms/op
Iteration   3: 3.065 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.074 ±(99.9%) 0.559 ms/op [Average]
  (min, avg, max) = (3.049, 3.074, 3.109), stdev = 0.031
  CI (99.9%): [2.516, 3.633] (assumes normal distribution)


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
# Warmup Iteration   1: 4.896 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.960 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.905 ±(99.9%) 0.030 ms/op
Iteration   1: 3.818 ±(99.9%) 0.009 ms/op
Iteration   2: 3.811 ±(99.9%) 0.021 ms/op
Iteration   3: 3.864 ±(99.9%) 0.033 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.831 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.811, 3.831, 3.864), stdev = 0.029
  CI (99.9%): [3.300, 4.362] (assumes normal distribution)


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
# Warmup Iteration   1: 4.096 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.183 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.084 ±(99.9%) 0.006 ms/op
Iteration   1: 3.188 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.757 ms/op
                 createUser·p0.50:   3.166 ms/op
                 createUser·p0.90:   3.813 ms/op
                 createUser·p0.95:   3.949 ms/op
                 createUser·p0.99:   4.399 ms/op
                 createUser·p0.999:  9.155 ms/op
                 createUser·p0.9999: 12.123 ms/op
                 createUser·p1.00:   17.269 ms/op

Iteration   2: 3.097 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.408 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.625 ms/op
                 createUser·p0.95:   3.789 ms/op
                 createUser·p0.99:   4.530 ms/op
                 createUser·p0.999:  10.617 ms/op
                 createUser·p0.9999: 15.002 ms/op
                 createUser·p1.00:   15.319 ms/op

Iteration   3: 3.055 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.656 ms/op
                 createUser·p0.50:   3.019 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.625 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  10.794 ms/op
                 createUser·p0.9999: 20.858 ms/op
                 createUser·p1.00:   21.234 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 308300
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12751 
    [ 2.500,  5.000) = 293794 
    [ 5.000,  7.500) = 1118 
    [ 7.500, 10.000) = 322 
    [10.000, 12.500) = 158 
    [12.500, 15.000) = 66 
    [15.000, 17.500) = 48 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 16 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.408 ms/op
     p(50.0000) =      3.072 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      4.407 ms/op
     p(99.9000) =     10.055 ms/op
     p(99.9900) =     17.891 ms/op
     p(99.9990) =     21.190 ms/op
     p(99.9999) =     21.234 ms/op
    p(100.0000) =     21.234 ms/op


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
# Warmup Iteration   1: 3.766 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 3.001 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.982 ±(99.9%) 0.006 ms/op
Iteration   1: 2.886 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.721 ms/op
                 existUser·p0.50:   2.863 ms/op
                 existUser·p0.90:   3.375 ms/op
                 existUser·p0.95:   3.703 ms/op
                 existUser·p0.99:   4.514 ms/op
                 existUser·p0.999:  7.900 ms/op
                 existUser·p0.9999: 14.335 ms/op
                 existUser·p1.00:   14.549 ms/op

Iteration   2: 2.918 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.669 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.707 ms/op
                 existUser·p0.99:   4.456 ms/op
                 existUser·p0.999:  7.620 ms/op
                 existUser·p0.9999: 12.519 ms/op
                 existUser·p1.00:   12.911 ms/op

Iteration   3: 2.926 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.660 ms/op
                 existUser·p0.50:   2.916 ms/op
                 existUser·p0.90:   3.441 ms/op
                 existUser·p0.95:   3.666 ms/op
                 existUser·p0.99:   4.399 ms/op
                 existUser·p0.999:  8.562 ms/op
                 existUser·p0.9999: 17.859 ms/op
                 existUser·p1.00:   18.514 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 329823
  mean =      2.910 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 3125 
    [ 1.250,  2.500) = 39027 
    [ 2.500,  3.750) = 274307 
    [ 3.750,  5.000) = 11707 
    [ 5.000,  6.250) = 874 
    [ 6.250,  7.500) = 391 
    [ 7.500,  8.750) = 128 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 46 
    [12.500, 13.750) = 66 
    [13.750, 15.000) = 40 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.660 ms/op
     p(50.0000) =      2.892 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.690 ms/op
     p(99.0000) =      4.465 ms/op
     p(99.9000) =      8.159 ms/op
     p(99.9900) =     14.402 ms/op
     p(99.9990) =     18.439 ms/op
     p(99.9999) =     18.514 ms/op
    p(100.0000) =     18.514 ms/op


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
# Warmup Iteration   1: 3.898 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.164 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.099 ±(99.9%) 0.007 ms/op
Iteration   1: 3.088 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.835 ms/op
                 getUser·p0.50:   3.047 ms/op
                 getUser·p0.90:   3.539 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.522 ms/op
                 getUser·p0.999:  11.911 ms/op
                 getUser·p0.9999: 16.377 ms/op
                 getUser·p1.00:   20.087 ms/op

Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.649 ms/op
                 getUser·p0.50:   3.097 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   3.830 ms/op
                 getUser·p0.99:   4.108 ms/op
                 getUser·p0.999:  8.234 ms/op
                 getUser·p0.9999: 16.433 ms/op
                 getUser·p1.00:   17.596 ms/op

Iteration   3: 3.058 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.564 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.502 ms/op
                 getUser·p0.95:   3.650 ms/op
                 getUser·p0.99:   4.301 ms/op
                 getUser·p0.999:  8.493 ms/op
                 getUser·p0.9999: 19.366 ms/op
                 getUser·p1.00:   19.661 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 310178
  mean =      3.094 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8546 
    [ 2.500,  5.000) = 300055 
    [ 5.000,  7.500) = 1121 
    [ 7.500, 10.000) = 165 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.564 ms/op
     p(50.0000) =      3.056 ms/op
     p(90.0000) =      3.568 ms/op
     p(95.0000) =      3.740 ms/op
     p(99.0000) =      4.293 ms/op
     p(99.9000) =      9.008 ms/op
     p(99.9900) =     17.596 ms/op
     p(99.9990) =     19.654 ms/op
     p(99.9999) =     20.087 ms/op
    p(100.0000) =     20.087 ms/op


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
# Warmup Iteration   1: 5.071 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.979 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.928 ±(99.9%) 0.010 ms/op
Iteration   1: 3.861 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.996 ms/op
                 listUser·p0.50:   3.781 ms/op
                 listUser·p0.90:   4.301 ms/op
                 listUser·p0.95:   5.079 ms/op
                 listUser·p0.99:   6.627 ms/op
                 listUser·p0.999:  13.599 ms/op
                 listUser·p0.9999: 19.431 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   2: 3.935 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.473 ms/op
                 listUser·p0.95:   5.538 ms/op
                 listUser·p0.99:   6.718 ms/op
                 listUser·p0.999:  13.550 ms/op
                 listUser·p0.9999: 24.219 ms/op
                 listUser·p1.00:   24.609 ms/op

Iteration   3: 3.880 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.768 ms/op
                 listUser·p0.90:   4.364 ms/op
                 listUser·p0.95:   5.554 ms/op
                 listUser·p0.99:   6.603 ms/op
                 listUser·p0.999:  17.205 ms/op
                 listUser·p0.9999: 27.796 ms/op
                 listUser·p1.00:   28.312 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 246726
  mean =      3.892 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3999 
    [ 2.500,  5.000) = 227258 
    [ 5.000,  7.500) = 14184 
    [ 7.500, 10.000) = 622 
    [10.000, 12.500) = 216 
    [12.500, 15.000) = 262 
    [15.000, 17.500) = 63 
    [17.500, 20.000) = 63 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 34 
    [25.000, 27.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.909 ms/op
     p(50.0000) =      3.793 ms/op
     p(90.0000) =      4.366 ms/op
     p(95.0000) =      5.415 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     14.247 ms/op
     p(99.9900) =     24.345 ms/op
     p(99.9990) =     28.132 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.300 ± 3.940  ops/ms
ClientGrpc.existUser                       thrpt       3  10.997 ± 7.183  ops/ms
ClientGrpc.getUser                         thrpt       3  10.375 ± 2.761  ops/ms
ClientGrpc.listUser                        thrpt       3   8.275 ± 1.260  ops/ms
ClientGrpc.createUser                       avgt       3   3.062 ± 0.199   ms/op
ClientGrpc.existUser                        avgt       3   2.900 ± 0.242   ms/op
ClientGrpc.getUser                          avgt       3   3.074 ± 0.559   ms/op
ClientGrpc.listUser                         avgt       3   3.831 ± 0.531   ms/op
ClientGrpc.createUser                     sample  308300   3.113 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.408           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.072           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.834           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.407           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.055           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          17.891           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.234           ms/op
ClientGrpc.existUser                      sample  329823   2.910 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.660           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.892           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.690           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.465           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.159           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          14.402           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.514           ms/op
ClientGrpc.getUser                        sample  310178   3.094 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.564           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.056           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.568           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.740           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.293           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.008           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.596           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.087           ms/op
ClientGrpc.listUser                       sample  246726   3.892 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.909           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.793           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.366           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.415           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.644           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.247           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.345           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.312           ms/op
