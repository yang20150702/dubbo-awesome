# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.627 ops/ms
# Warmup Iteration   2: 4.772 ops/ms
# Warmup Iteration   3: 6.719 ops/ms
Iteration   1: 6.959 ops/ms
Iteration   2: 6.803 ops/ms
Iteration   3: 6.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  6.917 ±(99.9%) 1.814 ops/ms [Average]
  (min, avg, max) = (6.803, 6.917, 6.988), stdev = 0.099
  CI (99.9%): [5.103, 8.731] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 4.448 ops/ms
# Warmup Iteration   2: 7.145 ops/ms
# Warmup Iteration   3: 7.613 ops/ms
Iteration   1: 7.453 ops/ms
Iteration   2: 7.488 ops/ms
Iteration   3: 7.277 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  7.406 ±(99.9%) 2.064 ops/ms [Average]
  (min, avg, max) = (7.277, 7.406, 7.488), stdev = 0.113
  CI (99.9%): [5.342, 9.470] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 3.892 ops/ms
# Warmup Iteration   2: 6.492 ops/ms
# Warmup Iteration   3: 6.695 ops/ms
Iteration   1: 6.962 ops/ms
Iteration   2: 6.997 ops/ms
Iteration   3: 6.979 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  6.979 ±(99.9%) 0.320 ops/ms [Average]
  (min, avg, max) = (6.962, 6.979, 6.997), stdev = 0.018
  CI (99.9%): [6.660, 7.299] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 3.446 ops/ms
# Warmup Iteration   2: 5.122 ops/ms
# Warmup Iteration   3: 5.324 ops/ms
Iteration   1: 5.375 ops/ms
Iteration   2: 5.462 ops/ms
Iteration   3: 5.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.470 ±(99.9%) 1.823 ops/ms [Average]
  (min, avg, max) = (5.375, 5.470, 5.574), stdev = 0.100
  CI (99.9%): [3.647, 7.294] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 7.275 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.884 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.735 ±(99.9%) 0.004 ms/op
Iteration   1: 4.668 ±(99.9%) 0.004 ms/op
Iteration   2: 4.719 ±(99.9%) 0.003 ms/op
Iteration   3: 4.673 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.687 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (4.668, 4.687, 4.719), stdev = 0.028
  CI (99.9%): [4.173, 5.200] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 6.153 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.490 ±(99.9%) 0.004 ms/op
Iteration   1: 4.483 ±(99.9%) 0.004 ms/op
Iteration   2: 4.440 ±(99.9%) 0.004 ms/op
Iteration   3: 4.473 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  4.465 ±(99.9%) 0.411 ms/op [Average]
  (min, avg, max) = (4.440, 4.465, 4.483), stdev = 0.023
  CI (99.9%): [4.054, 4.876] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 6.763 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.839 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.772 ±(99.9%) 0.006 ms/op
Iteration   1: 4.701 ±(99.9%) 0.003 ms/op
Iteration   2: 4.616 ±(99.9%) 0.003 ms/op
Iteration   3: 4.652 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  4.656 ±(99.9%) 0.775 ms/op [Average]
  (min, avg, max) = (4.616, 4.656, 4.701), stdev = 0.042
  CI (99.9%): [3.882, 5.431] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 8.608 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 5.955 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 5.634 ±(99.9%) 0.017 ms/op
Iteration   1: 5.536 ±(99.9%) 0.009 ms/op
Iteration   2: 5.424 ±(99.9%) 0.010 ms/op
Iteration   3: 5.551 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.503 ±(99.9%) 1.266 ms/op [Average]
  (min, avg, max) = (5.424, 5.503, 5.551), stdev = 0.069
  CI (99.9%): [4.237, 6.769] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 6.830 ±(99.9%) 0.085 ms/op
# Warmup Iteration   2: 4.949 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.632 ±(99.9%) 0.016 ms/op
Iteration   1: 4.564 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.182 ms/op
                 createUser·p0.50:   4.440 ms/op
                 createUser·p0.90:   5.808 ms/op
                 createUser·p0.95:   6.242 ms/op
                 createUser·p0.99:   7.648 ms/op
                 createUser·p0.999:  13.658 ms/op
                 createUser·p0.9999: 21.199 ms/op
                 createUser·p1.00:   21.660 ms/op

Iteration   2: 4.493 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.190 ms/op
                 createUser·p0.50:   4.375 ms/op
                 createUser·p0.90:   5.644 ms/op
                 createUser·p0.95:   6.013 ms/op
                 createUser·p0.99:   7.512 ms/op
                 createUser·p0.999:  11.348 ms/op
                 createUser·p0.9999: 22.774 ms/op
                 createUser·p1.00:   23.364 ms/op

Iteration   3: 4.635 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.966 ms/op
                 createUser·p0.50:   4.530 ms/op
                 createUser·p0.90:   5.890 ms/op
                 createUser·p0.95:   6.300 ms/op
                 createUser·p0.99:   8.307 ms/op
                 createUser·p0.999:  13.140 ms/op
                 createUser·p0.9999: 22.528 ms/op
                 createUser·p1.00:   23.626 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 210322
  mean =      4.563 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2921 
    [ 2.500,  5.000) = 146794 
    [ 5.000,  7.500) = 57991 
    [ 7.500, 10.000) = 2004 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 101 
    [15.000, 17.500) = 17 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 18 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.966 ms/op
     p(50.0000) =      4.440 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.193 ms/op
     p(99.0000) =      7.807 ms/op
     p(99.9000) =     13.129 ms/op
     p(99.9900) =     22.446 ms/op
     p(99.9990) =     23.330 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.491 ±(99.9%) 0.075 ms/op
# Warmup Iteration   2: 4.681 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 4.469 ±(99.9%) 0.013 ms/op
Iteration   1: 4.499 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.241 ms/op
                 existUser·p0.50:   4.391 ms/op
                 existUser·p0.90:   5.677 ms/op
                 existUser·p0.95:   6.087 ms/op
                 existUser·p0.99:   8.159 ms/op
                 existUser·p0.999:  13.320 ms/op
                 existUser·p0.9999: 18.539 ms/op
                 existUser·p1.00:   18.940 ms/op

Iteration   2: 4.176 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   4.067 ms/op
                 existUser·p0.90:   5.161 ms/op
                 existUser·p0.95:   5.612 ms/op
                 existUser·p0.99:   7.397 ms/op
                 existUser·p0.999:  10.201 ms/op
                 existUser·p0.9999: 22.020 ms/op
                 existUser·p1.00:   23.757 ms/op

Iteration   3: 4.365 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   0.962 ms/op
                 existUser·p0.50:   4.202 ms/op
                 existUser·p0.90:   5.521 ms/op
                 existUser·p0.95:   5.997 ms/op
                 existUser·p0.99:   8.438 ms/op
                 existUser·p0.999:  12.141 ms/op
                 existUser·p0.9999: 31.850 ms/op
                 existUser·p1.00:   32.145 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 221260
  mean =      4.342 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3866 
    [ 2.500,  5.000) = 172855 
    [ 5.000,  7.500) = 41655 
    [ 7.500, 10.000) = 2221 
    [10.000, 12.500) = 445 
    [12.500, 15.000) = 112 
    [15.000, 17.500) = 10 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.962 ms/op
     p(50.0000) =      4.194 ms/op
     p(90.0000) =      5.489 ms/op
     p(95.0000) =      5.931 ms/op
     p(99.0000) =      7.938 ms/op
     p(99.9000) =     12.468 ms/op
     p(99.9900) =     31.158 ms/op
     p(99.9990) =     32.066 ms/op
     p(99.9999) =     32.145 ms/op
    p(100.0000) =     32.145 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 6.873 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.634 ±(99.9%) 0.015 ms/op
Iteration   1: 4.752 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.157 ms/op
                 getUser·p0.50:   4.620 ms/op
                 getUser·p0.90:   6.095 ms/op
                 getUser·p0.95:   6.497 ms/op
                 getUser·p0.99:   8.184 ms/op
                 getUser·p0.999:  14.719 ms/op
                 getUser·p0.9999: 16.315 ms/op
                 getUser·p1.00:   16.548 ms/op

Iteration   2: 4.727 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   0.951 ms/op
                 getUser·p0.50:   4.563 ms/op
                 getUser·p0.90:   6.160 ms/op
                 getUser·p0.95:   6.676 ms/op
                 getUser·p0.99:   8.978 ms/op
                 getUser·p0.999:  15.450 ms/op
                 getUser·p0.9999: 18.128 ms/op
                 getUser·p1.00:   18.776 ms/op

Iteration   3: 4.705 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   0.974 ms/op
                 getUser·p0.50:   4.473 ms/op
                 getUser·p0.90:   6.095 ms/op
                 getUser·p0.95:   6.817 ms/op
                 getUser·p0.99:   9.896 ms/op
                 getUser·p0.999:  15.319 ms/op
                 getUser·p0.9999: 21.863 ms/op
                 getUser·p1.00:   22.807 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 203017
  mean =      4.728 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2770 
    [ 2.500,  5.000) = 130659 
    [ 5.000,  7.500) = 64960 
    [ 7.500, 10.000) = 3256 
    [10.000, 12.500) = 841 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 137 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 24 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      4.547 ms/op
     p(90.0000) =      6.119 ms/op
     p(95.0000) =      6.644 ms/op
     p(99.0000) =      9.044 ms/op
     p(99.9000) =     14.942 ms/op
     p(99.9900) =     20.764 ms/op
     p(99.9990) =     22.467 ms/op
     p(99.9999) =     22.807 ms/op
    p(100.0000) =     22.807 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.710 ±(99.9%) 0.115 ms/op
# Warmup Iteration   2: 5.963 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 5.621 ±(99.9%) 0.021 ms/op
Iteration   1: 5.507 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   1.909 ms/op
                 listUser·p0.50:   5.202 ms/op
                 listUser·p0.90:   7.447 ms/op
                 listUser·p0.95:   8.389 ms/op
                 listUser·p0.99:   11.092 ms/op
                 listUser·p0.999:  19.586 ms/op
                 listUser·p0.9999: 22.839 ms/op
                 listUser·p1.00:   23.724 ms/op

Iteration   2: 5.546 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.454 ms/op
                 listUser·p0.50:   5.284 ms/op
                 listUser·p0.90:   7.135 ms/op
                 listUser·p0.95:   8.208 ms/op
                 listUser·p0.99:   10.366 ms/op
                 listUser·p0.999:  21.110 ms/op
                 listUser·p0.9999: 32.758 ms/op
                 listUser·p1.00:   33.227 ms/op

Iteration   3: 5.464 ±(99.9%) 0.021 ms/op
                 listUser·p0.00:   1.079 ms/op
                 listUser·p0.50:   5.210 ms/op
                 listUser·p0.90:   7.143 ms/op
                 listUser·p0.95:   7.963 ms/op
                 listUser·p0.99:   10.154 ms/op
                 listUser·p0.999:  24.392 ms/op
                 listUser·p0.9999: 26.673 ms/op
                 listUser·p1.00:   29.393 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 174418
  mean =      5.506 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 169 
    [ 2.500,  5.000) = 68976 
    [ 5.000,  7.500) = 90608 
    [ 7.500, 10.000) = 12317 
    [10.000, 12.500) = 1573 
    [12.500, 15.000) = 346 
    [15.000, 17.500) = 116 
    [17.500, 20.000) = 108 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.079 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.192 ms/op
     p(99.0000) =     10.584 ms/op
     p(99.9000) =     20.747 ms/op
     p(99.9900) =     30.769 ms/op
     p(99.9990) =     33.154 ms/op
     p(99.9999) =     33.227 ms/op
    p(100.0000) =     33.227 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   6.917 ± 1.814  ops/ms
ClientGrpc.existUser                       thrpt       3   7.406 ± 2.064  ops/ms
ClientGrpc.getUser                         thrpt       3   6.979 ± 0.320  ops/ms
ClientGrpc.listUser                        thrpt       3   5.470 ± 1.823  ops/ms
ClientGrpc.createUser                       avgt       3   4.687 ± 0.513   ms/op
ClientGrpc.existUser                        avgt       3   4.465 ± 0.411   ms/op
ClientGrpc.getUser                          avgt       3   4.656 ± 0.775   ms/op
ClientGrpc.listUser                         avgt       3   5.503 ± 1.266   ms/op
ClientGrpc.createUser                     sample  210322   4.563 ± 0.008   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.966           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           4.440           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           5.784           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           6.193           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           7.807           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          13.129           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          22.446           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.626           ms/op
ClientGrpc.existUser                      sample  221260   4.342 ± 0.008   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.962           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           4.194           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           5.489           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           7.938           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          12.468           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          31.158           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          32.145           ms/op
ClientGrpc.getUser                        sample  203017   4.728 ± 0.009   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.951           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           4.547           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           6.119           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           6.644           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           9.044           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          14.942           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          20.764           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.807           ms/op
ClientGrpc.listUser                       sample  174418   5.506 ± 0.012   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.079           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           5.235           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           7.250           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           8.192           ms/op
ClientGrpc.listUser:listUser·p0.99        sample          10.584           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          20.747           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          30.769           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          33.227           ms/op
