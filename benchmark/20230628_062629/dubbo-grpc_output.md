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
# Warmup Iteration   1: 2.991 ops/ms
# Warmup Iteration   2: 6.739 ops/ms
# Warmup Iteration   3: 8.027 ops/ms
Iteration   1: 8.564 ops/ms
Iteration   2: 8.499 ops/ms
Iteration   3: 8.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.532 ±(99.9%) 0.597 ops/ms [Average]
  (min, avg, max) = (8.499, 8.532, 8.564), stdev = 0.033
  CI (99.9%): [7.935, 9.129] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 6.207 ops/ms
# Warmup Iteration   2: 8.610 ops/ms
# Warmup Iteration   3: 9.179 ops/ms
Iteration   1: 9.241 ops/ms
Iteration   2: 9.255 ops/ms
Iteration   3: 9.200 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.232 ±(99.9%) 0.523 ops/ms [Average]
  (min, avg, max) = (9.200, 9.232, 9.255), stdev = 0.029
  CI (99.9%): [8.708, 9.755] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.119 ops/ms
# Warmup Iteration   2: 8.185 ops/ms
# Warmup Iteration   3: 8.424 ops/ms
Iteration   1: 8.605 ops/ms
Iteration   2: 8.675 ops/ms
Iteration   3: 8.493 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.591 ±(99.9%) 1.675 ops/ms [Average]
  (min, avg, max) = (8.493, 8.591, 8.675), stdev = 0.092
  CI (99.9%): [6.916, 10.266] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 5.118 ops/ms
# Warmup Iteration   2: 6.157 ops/ms
# Warmup Iteration   3: 6.626 ops/ms
Iteration   1: 6.766 ops/ms
Iteration   2: 6.777 ops/ms
Iteration   3: 6.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.771 ±(99.9%) 0.101 ops/ms [Average]
  (min, avg, max) = (6.766, 6.771, 6.777), stdev = 0.006
  CI (99.9%): [6.670, 6.873] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.385 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.875 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.804 ±(99.9%) 0.012 ms/op
Iteration   1: 3.656 ±(99.9%) 0.002 ms/op
Iteration   2: 3.680 ±(99.9%) 0.002 ms/op
Iteration   3: 3.722 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.686 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.656, 3.686, 3.722), stdev = 0.033
  CI (99.9%): [3.075, 4.297] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.990 ±(99.9%) 0.014 ms/op
# Warmup Iteration   2: 3.705 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.448 ±(99.9%) 0.003 ms/op
Iteration   1: 3.339 ±(99.9%) 0.005 ms/op
Iteration   2: 3.421 ±(99.9%) 0.003 ms/op
Iteration   3: 3.468 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.409 ±(99.9%) 1.187 ms/op [Average]
  (min, avg, max) = (3.339, 3.409, 3.468), stdev = 0.065
  CI (99.9%): [2.222, 4.596] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.467 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.842 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.684 ±(99.9%) 0.004 ms/op
Iteration   1: 3.729 ±(99.9%) 0.002 ms/op
Iteration   2: 3.652 ±(99.9%) 0.003 ms/op
Iteration   3: 3.570 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.650 ±(99.9%) 1.445 ms/op [Average]
  (min, avg, max) = (3.570, 3.650, 3.729), stdev = 0.079
  CI (99.9%): [2.205, 5.095] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 6.530 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 4.882 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.739 ±(99.9%) 0.009 ms/op
Iteration   1: 4.790 ±(99.9%) 0.014 ms/op
Iteration   2: 4.713 ±(99.9%) 0.011 ms/op
Iteration   3: 4.727 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.743 ±(99.9%) 0.753 ms/op [Average]
  (min, avg, max) = (4.713, 4.743, 4.790), stdev = 0.041
  CI (99.9%): [3.990, 5.496] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.409 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.829 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.656 ±(99.9%) 0.008 ms/op
Iteration   1: 3.698 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.792 ms/op
                 createUser·p0.50:   3.617 ms/op
                 createUser·p0.90:   4.317 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   6.169 ms/op
                 createUser·p0.999:  16.777 ms/op
                 createUser·p0.9999: 20.154 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   2: 3.674 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.847 ms/op
                 createUser·p0.50:   3.625 ms/op
                 createUser·p0.90:   4.579 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   6.275 ms/op
                 createUser·p0.999:  10.402 ms/op
                 createUser·p0.9999: 27.230 ms/op
                 createUser·p1.00:   27.460 ms/op

Iteration   3: 3.639 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.913 ms/op
                 createUser·p0.50:   3.592 ms/op
                 createUser·p0.90:   4.227 ms/op
                 createUser·p0.95:   4.514 ms/op
                 createUser·p0.99:   5.743 ms/op
                 createUser·p0.999:  7.932 ms/op
                 createUser·p0.9999: 23.246 ms/op
                 createUser·p1.00:   23.691 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 261399
  mean =      3.670 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8761 
    [ 2.500,  5.000) = 244245 
    [ 5.000,  7.500) = 7497 
    [ 7.500, 10.000) = 539 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 61 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 30 

  Percentiles, ms/op:
      p(0.0000) =      0.792 ms/op
     p(50.0000) =      3.609 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.735 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     11.452 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     27.427 ms/op
     p(99.9999) =     27.460 ms/op
    p(100.0000) =     27.460 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.925 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.713 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.008 ms/op
Iteration   1: 3.488 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.869 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.071 ms/op
                 existUser·p0.95:   4.465 ms/op
                 existUser·p0.99:   5.530 ms/op
                 existUser·p0.999:  9.672 ms/op
                 existUser·p0.9999: 22.047 ms/op
                 existUser·p1.00:   22.512 ms/op

Iteration   2: 3.484 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.428 ms/op
                 existUser·p0.90:   4.067 ms/op
                 existUser·p0.95:   4.350 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  7.948 ms/op
                 existUser·p0.9999: 16.495 ms/op
                 existUser·p1.00:   16.744 ms/op

Iteration   3: 3.448 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.931 ms/op
                 existUser·p0.50:   3.412 ms/op
                 existUser·p0.90:   3.932 ms/op
                 existUser·p0.95:   4.227 ms/op
                 existUser·p0.99:   5.546 ms/op
                 existUser·p0.999:  11.096 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.826 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 276233
  mean =      3.473 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6730 
    [ 2.500,  5.000) = 264891 
    [ 5.000,  7.500) = 3922 
    [ 7.500, 10.000) = 418 
    [10.000, 12.500) = 143 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 31 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.869 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.014 ms/op
     p(95.0000) =      4.366 ms/op
     p(99.0000) =      5.464 ms/op
     p(99.9000) =      9.945 ms/op
     p(99.9900) =     20.787 ms/op
     p(99.9990) =     22.363 ms/op
     p(99.9999) =     22.512 ms/op
    p(100.0000) =     22.512 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.401 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.896 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.778 ±(99.9%) 0.010 ms/op
Iteration   1: 3.714 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.042 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.547 ms/op
                 getUser·p0.95:   4.891 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  9.903 ms/op
                 getUser·p0.9999: 22.688 ms/op
                 getUser·p1.00:   23.036 ms/op

Iteration   2: 3.637 ±(99.9%) 0.007 ms/op
                 getUser·p0.00:   0.975 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.227 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.898 ms/op
                 getUser·p0.999:  8.782 ms/op
                 getUser·p0.9999: 16.712 ms/op
                 getUser·p1.00:   17.072 ms/op

Iteration   3: 3.736 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.695 ms/op
                 getUser·p0.50:   3.650 ms/op
                 getUser·p0.90:   4.465 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.406 ms/op
                 getUser·p0.999:  10.522 ms/op
                 getUser·p0.9999: 28.326 ms/op
                 getUser·p1.00:   29.819 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 259636
  mean =      3.695 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9085 
    [ 2.500,  5.000) = 241424 
    [ 5.000,  7.500) = 8191 
    [ 7.500, 10.000) = 712 
    [10.000, 12.500) = 65 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.633 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.792 ms/op
     p(99.0000) =      6.152 ms/op
     p(99.9000) =      9.656 ms/op
     p(99.9900) =     27.165 ms/op
     p(99.9990) =     29.741 ms/op
     p(99.9999) =     29.819 ms/op
    p(100.0000) =     29.819 ms/op


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
# Warmup Iteration   1: 7.131 ±(99.9%) 0.076 ms/op
# Warmup Iteration   2: 4.980 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.921 ±(99.9%) 0.016 ms/op
Iteration   1: 4.813 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.645 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.119 ms/op
                 listUser·p0.95:   6.857 ms/op
                 listUser·p0.99:   8.913 ms/op
                 listUser·p0.999:  16.400 ms/op
                 listUser·p0.9999: 20.120 ms/op
                 listUser·p1.00:   20.578 ms/op

Iteration   2: 4.797 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.503 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   6.971 ms/op
                 listUser·p0.99:   8.471 ms/op
                 listUser·p0.999:  15.841 ms/op
                 listUser·p0.9999: 21.965 ms/op
                 listUser·p1.00:   22.217 ms/op

Iteration   3: 4.407 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   0.834 ms/op
                 listUser·p0.50:   4.211 ms/op
                 listUser·p0.90:   5.399 ms/op
                 listUser·p0.95:   6.455 ms/op
                 listUser·p0.99:   8.307 ms/op
                 listUser·p0.999:  21.070 ms/op
                 listUser·p0.9999: 25.354 ms/op
                 listUser·p1.00:   26.018 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 205683
  mean =      4.665 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 546 
    [ 2.500,  5.000) = 158016 
    [ 5.000,  7.500) = 41806 
    [ 7.500, 10.000) = 4507 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 95 
    [20.000, 22.500) = 75 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.834 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.972 ms/op
     p(95.0000) =      6.791 ms/op
     p(99.0000) =      8.569 ms/op
     p(99.9000) =     17.859 ms/op
     p(99.9900) =     24.000 ms/op
     p(99.9990) =     25.852 ms/op
     p(99.9999) =     26.018 ms/op
    p(100.0000) =     26.018 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.532 ± 0.597  ops/ms
ClientGrpc.existUser                       thrpt       3   9.232 ± 0.523  ops/ms
ClientGrpc.getUser                         thrpt       3   8.591 ± 1.675  ops/ms
ClientGrpc.listUser                        thrpt       3   6.771 ± 0.101  ops/ms
ClientGrpc.createUser                       avgt       3   3.686 ± 0.611   ms/op
ClientGrpc.existUser                        avgt       3   3.409 ± 1.187   ms/op
ClientGrpc.getUser                          avgt       3   3.650 ± 1.445   ms/op
ClientGrpc.listUser                         avgt       3   4.743 ± 0.753   ms/op
ClientGrpc.createUser                     sample  261399   3.670 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.792           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.609           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.375           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.735           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.054           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.452           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          25.068           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          27.460           ms/op
ClientGrpc.existUser                      sample  276233   3.473 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.869           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.014           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.366           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.464           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           9.945           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          20.787           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.512           ms/op
ClientGrpc.getUser                        sample  259636   3.695 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.695           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.633           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.424           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.792           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.152           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.656           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          27.165           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          29.819           ms/op
ClientGrpc.listUser                       sample  205683   4.665 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.834           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.456           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.972           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.791           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.569           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.859           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.000           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.018           ms/op
