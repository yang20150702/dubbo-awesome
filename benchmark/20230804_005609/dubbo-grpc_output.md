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
# Warmup Iteration   1: 4.187 ops/ms
# Warmup Iteration   2: 8.938 ops/ms
# Warmup Iteration   3: 9.809 ops/ms
Iteration   1: 10.510 ops/ms
Iteration   2: 10.612 ops/ms
Iteration   3: 10.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.522 ±(99.9%) 1.532 ops/ms [Average]
  (min, avg, max) = (10.445, 10.522, 10.612), stdev = 0.084
  CI (99.9%): [8.990, 12.055] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.498 ops/ms
# Warmup Iteration   2: 10.510 ops/ms
# Warmup Iteration   3: 10.832 ops/ms
Iteration   1: 10.993 ops/ms
Iteration   2: 10.696 ops/ms
Iteration   3: 10.989 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.893 ±(99.9%) 3.108 ops/ms [Average]
  (min, avg, max) = (10.696, 10.893, 10.993), stdev = 0.170
  CI (99.9%): [7.785, 14.001] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:52
# Fork: 1 of 1
# Warmup Iteration   1: 6.943 ops/ms
# Warmup Iteration   2: 9.873 ops/ms
# Warmup Iteration   3: 10.227 ops/ms
Iteration   1: 10.208 ops/ms
Iteration   2: 10.303 ops/ms
Iteration   3: 10.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.263 ±(99.9%) 0.888 ops/ms [Average]
  (min, avg, max) = (10.208, 10.263, 10.303), stdev = 0.049
  CI (99.9%): [9.374, 11.151] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.006 ops/ms
# Warmup Iteration   2: 7.376 ops/ms
# Warmup Iteration   3: 7.951 ops/ms
Iteration   1: 7.722 ops/ms
Iteration   2: 7.780 ops/ms
Iteration   3: 7.735 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  7.746 ±(99.9%) 0.562 ops/ms [Average]
  (min, avg, max) = (7.722, 7.746, 7.780), stdev = 0.031
  CI (99.9%): [7.184, 8.308] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:41
# Fork: 1 of 1
# Warmup Iteration   1: 4.372 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.200 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 3.085 ±(99.9%) 0.003 ms/op
Iteration   1: 3.129 ±(99.9%) 0.002 ms/op
Iteration   2: 3.086 ±(99.9%) 0.003 ms/op
Iteration   3: 3.058 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.091 ±(99.9%) 0.646 ms/op [Average]
  (min, avg, max) = (3.058, 3.091, 3.129), stdev = 0.035
  CI (99.9%): [2.445, 3.737] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:36
# Fork: 1 of 1
# Warmup Iteration   1: 3.999 ±(99.9%) 0.013 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 2.927 ±(99.9%) 0.002 ms/op
Iteration   1: 2.948 ±(99.9%) 0.003 ms/op
Iteration   2: 2.993 ±(99.9%) 0.002 ms/op
Iteration   3: 2.948 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.963 ±(99.9%) 0.470 ms/op [Average]
  (min, avg, max) = (2.948, 2.963, 2.993), stdev = 0.026
  CI (99.9%): [2.493, 3.433] (assumes normal distribution)


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
# Warmup Iteration   1: 4.258 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.149 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.113 ±(99.9%) 0.003 ms/op
Iteration   1: 3.088 ±(99.9%) 0.004 ms/op
Iteration   2: 3.044 ±(99.9%) 0.005 ms/op
Iteration   3: 3.082 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.071 ±(99.9%) 0.430 ms/op [Average]
  (min, avg, max) = (3.044, 3.071, 3.088), stdev = 0.024
  CI (99.9%): [2.641, 3.501] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 5.628 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 4.153 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.223 ±(99.9%) 0.019 ms/op
Iteration   1: 4.114 ±(99.9%) 0.012 ms/op
Iteration   2: 4.061 ±(99.9%) 0.013 ms/op
Iteration   3: 4.052 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.076 ±(99.9%) 0.613 ms/op [Average]
  (min, avg, max) = (4.052, 4.076, 4.114), stdev = 0.034
  CI (99.9%): [3.463, 4.689] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.282 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.246 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.111 ±(99.9%) 0.006 ms/op
Iteration   1: 3.102 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.043 ms/op
                 createUser·p0.90:   3.641 ms/op
                 createUser·p0.95:   3.875 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  8.125 ms/op
                 createUser·p0.9999: 12.627 ms/op
                 createUser·p1.00:   12.894 ms/op

Iteration   2: 3.137 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.999 ms/op
                 createUser·p0.50:   3.088 ms/op
                 createUser·p0.90:   3.645 ms/op
                 createUser·p0.95:   3.809 ms/op
                 createUser·p0.99:   4.514 ms/op
                 createUser·p0.999:  10.208 ms/op
                 createUser·p0.9999: 14.579 ms/op
                 createUser·p1.00:   14.762 ms/op

Iteration   3: 3.058 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.653 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.654 ms/op
                 createUser·p0.95:   3.919 ms/op
                 createUser·p0.99:   4.809 ms/op
                 createUser·p0.999:  14.107 ms/op
                 createUser·p0.9999: 17.304 ms/op
                 createUser·p1.00:   18.219 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 309771
  mean =      3.099 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 879 
    [ 1.250,  2.500) = 17595 
    [ 2.500,  3.750) = 269367 
    [ 3.750,  5.000) = 19480 
    [ 5.000,  6.250) = 1200 
    [ 6.250,  7.500) = 539 
    [ 7.500,  8.750) = 291 
    [ 8.750, 10.000) = 120 
    [10.000, 11.250) = 8 
    [11.250, 12.500) = 51 
    [12.500, 13.750) = 56 
    [13.750, 15.000) = 96 
    [15.000, 16.250) = 42 
    [16.250, 17.500) = 39 
    [17.500, 18.750) = 8 

  Percentiles, ms/op:
      p(0.0000) =      0.653 ms/op
     p(50.0000) =      3.060 ms/op
     p(90.0000) =      3.650 ms/op
     p(95.0000) =      3.863 ms/op
     p(99.0000) =      4.743 ms/op
     p(99.9000) =      9.769 ms/op
     p(99.9900) =     16.646 ms/op
     p(99.9990) =     18.186 ms/op
     p(99.9999) =     18.219 ms/op
    p(100.0000) =     18.219 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 4.151 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.073 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.932 ±(99.9%) 0.006 ms/op
Iteration   1: 2.896 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.772 ms/op
                 existUser·p0.50:   2.892 ms/op
                 existUser·p0.90:   3.232 ms/op
                 existUser·p0.95:   3.383 ms/op
                 existUser·p0.99:   4.080 ms/op
                 existUser·p0.999:  6.598 ms/op
                 existUser·p0.9999: 17.824 ms/op
                 existUser·p1.00:   19.399 ms/op

Iteration   2: 2.962 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.732 ms/op
                 existUser·p0.50:   2.920 ms/op
                 existUser·p0.90:   3.428 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.311 ms/op
                 existUser·p0.999:  8.585 ms/op
                 existUser·p0.9999: 17.701 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   3: 2.973 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.694 ms/op
                 existUser·p0.50:   2.937 ms/op
                 existUser·p0.90:   3.432 ms/op
                 existUser·p0.95:   3.600 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  7.914 ms/op
                 existUser·p0.9999: 20.200 ms/op
                 existUser·p1.00:   21.266 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 326185
  mean =      2.944 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24393 
    [ 2.500,  5.000) = 300253 
    [ 5.000,  7.500) = 1147 
    [ 7.500, 10.000) = 216 
    [10.000, 12.500) = 16 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 62 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 11 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.694 ms/op
     p(50.0000) =      2.912 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.572 ms/op
     p(99.0000) =      4.219 ms/op
     p(99.9000) =      7.846 ms/op
     p(99.9900) =     19.137 ms/op
     p(99.9990) =     20.537 ms/op
     p(99.9999) =     21.266 ms/op
    p(100.0000) =     21.266 ms/op


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
# Warmup Iteration   1: 4.042 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 3.177 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.104 ±(99.9%) 0.007 ms/op
Iteration   1: 3.052 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.694 ms/op
                 getUser·p0.50:   3.043 ms/op
                 getUser·p0.90:   3.551 ms/op
                 getUser·p0.95:   3.842 ms/op
                 getUser·p0.99:   5.022 ms/op
                 getUser·p0.999:  9.293 ms/op
                 getUser·p0.9999: 13.575 ms/op
                 getUser·p1.00:   13.763 ms/op

Iteration   2: 3.068 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.596 ms/op
                 getUser·p0.50:   3.035 ms/op
                 getUser·p0.90:   3.580 ms/op
                 getUser·p0.95:   3.809 ms/op
                 getUser·p0.99:   4.669 ms/op
                 getUser·p0.999:  8.359 ms/op
                 getUser·p0.9999: 18.547 ms/op
                 getUser·p1.00:   18.874 ms/op

Iteration   3: 3.138 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.670 ms/op
                 getUser·p0.50:   3.088 ms/op
                 getUser·p0.90:   3.686 ms/op
                 getUser·p0.95:   3.829 ms/op
                 getUser·p0.99:   4.391 ms/op
                 getUser·p0.999:  9.654 ms/op
                 getUser·p0.9999: 19.124 ms/op
                 getUser·p1.00:   19.530 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 311008
  mean =      3.085 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 618 
    [ 1.250,  2.500) = 17817 
    [ 2.500,  3.750) = 272414 
    [ 3.750,  5.000) = 17894 
    [ 5.000,  6.250) = 1251 
    [ 6.250,  7.500) = 451 
    [ 7.500,  8.750) = 204 
    [ 8.750, 10.000) = 93 
    [10.000, 11.250) = 10 
    [11.250, 12.500) = 14 
    [12.500, 13.750) = 88 
    [13.750, 15.000) = 58 
    [15.000, 16.250) = 17 
    [16.250, 17.500) = 31 
    [17.500, 18.750) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.596 ms/op
     p(50.0000) =      3.052 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      4.751 ms/op
     p(99.9000) =      9.060 ms/op
     p(99.9900) =     18.153 ms/op
     p(99.9990) =     19.424 ms/op
     p(99.9999) =     19.530 ms/op
    p(100.0000) =     19.530 ms/op


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
# Warmup Iteration   1: 4.667 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.533 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.114 ±(99.9%) 0.012 ms/op
Iteration   1: 4.112 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.909 ms/op
                 listUser·p0.50:   3.957 ms/op
                 listUser·p0.90:   5.038 ms/op
                 listUser·p0.95:   5.890 ms/op
                 listUser·p0.99:   7.326 ms/op
                 listUser·p0.999:  12.873 ms/op
                 listUser·p0.9999: 21.347 ms/op
                 listUser·p1.00:   21.725 ms/op

Iteration   2: 4.016 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   0.876 ms/op
                 listUser·p0.50:   3.858 ms/op
                 listUser·p0.90:   4.997 ms/op
                 listUser·p0.95:   5.865 ms/op
                 listUser·p0.99:   7.111 ms/op
                 listUser·p0.999:  16.597 ms/op
                 listUser·p0.9999: 20.415 ms/op
                 listUser·p1.00:   21.987 ms/op

Iteration   3: 4.103 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.008 ms/op
                 listUser·p0.50:   3.932 ms/op
                 listUser·p0.90:   5.014 ms/op
                 listUser·p0.95:   5.898 ms/op
                 listUser·p0.99:   7.250 ms/op
                 listUser·p0.999:  24.475 ms/op
                 listUser·p0.9999: 27.957 ms/op
                 listUser·p1.00:   28.213 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 235644
  mean =      4.076 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2806 
    [ 2.500,  5.000) = 209017 
    [ 5.000,  7.500) = 22051 
    [ 7.500, 10.000) = 1234 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 70 
    [17.500, 20.000) = 57 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 39 

  Percentiles, ms/op:
      p(0.0000) =      0.876 ms/op
     p(50.0000) =      3.916 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.882 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     16.976 ms/op
     p(99.9900) =     27.263 ms/op
     p(99.9990) =     28.103 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:04

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.522 ± 1.532  ops/ms
ClientGrpc.existUser                       thrpt       3  10.893 ± 3.108  ops/ms
ClientGrpc.getUser                         thrpt       3  10.263 ± 0.888  ops/ms
ClientGrpc.listUser                        thrpt       3   7.746 ± 0.562  ops/ms
ClientGrpc.createUser                       avgt       3   3.091 ± 0.646   ms/op
ClientGrpc.existUser                        avgt       3   2.963 ± 0.470   ms/op
ClientGrpc.getUser                          avgt       3   3.071 ± 0.430   ms/op
ClientGrpc.listUser                         avgt       3   4.076 ± 0.613   ms/op
ClientGrpc.createUser                     sample  309771   3.099 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.653           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.060           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.650           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.863           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.743           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           9.769           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          16.646           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          18.219           ms/op
ClientGrpc.existUser                      sample  326185   2.944 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.694           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.912           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.219           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           7.846           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.137           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          21.266           ms/op
ClientGrpc.getUser                        sample  311008   3.085 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.596           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.052           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.625           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.826           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.751           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.060           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          18.153           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.530           ms/op
ClientGrpc.listUser                       sample  235644   4.076 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.876           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.916           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.014           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.882           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           7.225           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.976           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          27.263           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.213           ms/op
