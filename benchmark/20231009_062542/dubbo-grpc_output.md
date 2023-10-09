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
# Warmup Iteration   1: 3.099 ops/ms
# Warmup Iteration   2: 6.919 ops/ms
# Warmup Iteration   3: 8.104 ops/ms
Iteration   1: 8.526 ops/ms
Iteration   2: 8.530 ops/ms
Iteration   3: 8.805 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.620 ±(99.9%) 2.922 ops/ms [Average]
  (min, avg, max) = (8.526, 8.620, 8.805), stdev = 0.160
  CI (99.9%): [5.699, 11.542] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:03
# Fork: 1 of 1
# Warmup Iteration   1: 6.485 ops/ms
# Warmup Iteration   2: 8.440 ops/ms
# Warmup Iteration   3: 8.835 ops/ms
Iteration   1: 9.346 ops/ms
Iteration   2: 8.889 ops/ms
Iteration   3: 9.145 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.126 ±(99.9%) 4.178 ops/ms [Average]
  (min, avg, max) = (8.889, 9.126, 9.346), stdev = 0.229
  CI (99.9%): [4.949, 13.304] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 5.480 ops/ms
# Warmup Iteration   2: 7.900 ops/ms
# Warmup Iteration   3: 8.409 ops/ms
Iteration   1: 8.571 ops/ms
Iteration   2: 8.607 ops/ms
Iteration   3: 8.577 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.585 ±(99.9%) 0.353 ops/ms [Average]
  (min, avg, max) = (8.571, 8.585, 8.607), stdev = 0.019
  CI (99.9%): [8.232, 8.938] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 4.188 ops/ms
# Warmup Iteration   2: 6.363 ops/ms
# Warmup Iteration   3: 6.731 ops/ms
Iteration   1: 6.693 ops/ms
Iteration   2: 6.727 ops/ms
Iteration   3: 6.627 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.682 ±(99.9%) 0.926 ops/ms [Average]
  (min, avg, max) = (6.627, 6.682, 6.727), stdev = 0.051
  CI (99.9%): [5.756, 7.609] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 5.180 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.920 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.930 ±(99.9%) 0.018 ms/op
Iteration   1: 3.770 ±(99.9%) 0.004 ms/op
Iteration   2: 3.740 ±(99.9%) 0.003 ms/op
Iteration   3: 3.796 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.769 ±(99.9%) 0.513 ms/op [Average]
  (min, avg, max) = (3.740, 3.769, 3.796), stdev = 0.028
  CI (99.9%): [3.255, 4.282] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 4.694 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.734 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.602 ±(99.9%) 0.005 ms/op
Iteration   1: 3.533 ±(99.9%) 0.004 ms/op
Iteration   2: 3.518 ±(99.9%) 0.004 ms/op
Iteration   3: 3.532 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.528 ±(99.9%) 0.159 ms/op [Average]
  (min, avg, max) = (3.518, 3.528, 3.533), stdev = 0.009
  CI (99.9%): [3.369, 3.686] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 5.458 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.847 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.842 ±(99.9%) 0.004 ms/op
Iteration   1: 3.672 ±(99.9%) 0.003 ms/op
Iteration   2: 3.818 ±(99.9%) 0.006 ms/op
Iteration   3: 3.733 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.741 ±(99.9%) 1.341 ms/op [Average]
  (min, avg, max) = (3.672, 3.741, 3.818), stdev = 0.074
  CI (99.9%): [2.400, 5.082] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 7.001 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.907 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 4.899 ±(99.9%) 0.028 ms/op
Iteration   1: 4.987 ±(99.9%) 0.014 ms/op
Iteration   2: 4.584 ±(99.9%) 0.012 ms/op
Iteration   3: 4.934 ±(99.9%) 0.020 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.835 ±(99.9%) 3.999 ms/op [Average]
  (min, avg, max) = (4.584, 4.835, 4.987), stdev = 0.219
  CI (99.9%): [0.836, 8.834] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 5.245 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.924 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.784 ±(99.9%) 0.010 ms/op
Iteration   1: 3.734 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.962 ms/op
                 createUser·p0.50:   3.650 ms/op
                 createUser·p0.90:   4.506 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  8.837 ms/op
                 createUser·p0.9999: 15.479 ms/op
                 createUser·p1.00:   15.827 ms/op

Iteration   2: 3.692 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.907 ms/op
                 createUser·p0.50:   3.609 ms/op
                 createUser·p0.90:   4.456 ms/op
                 createUser·p0.95:   4.858 ms/op
                 createUser·p0.99:   6.798 ms/op
                 createUser·p0.999:  12.287 ms/op
                 createUser·p0.9999: 20.283 ms/op
                 createUser·p1.00:   20.414 ms/op

Iteration   3: 3.631 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.856 ms/op
                 createUser·p0.50:   3.604 ms/op
                 createUser·p0.90:   4.350 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.070 ms/op
                 createUser·p0.999:  16.904 ms/op
                 createUser·p0.9999: 18.455 ms/op
                 createUser·p1.00:   20.546 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260245
  mean =      3.685 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11685 
    [ 2.500,  5.000) = 238301 
    [ 5.000,  7.500) = 9022 
    [ 7.500, 10.000) = 878 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 39 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 25 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.856 ms/op
     p(50.0000) =      3.621 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.850 ms/op
     p(99.0000) =      6.406 ms/op
     p(99.9000) =     11.321 ms/op
     p(99.9900) =     19.945 ms/op
     p(99.9990) =     20.427 ms/op
     p(99.9999) =     20.546 ms/op
    p(100.0000) =     20.546 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 4.945 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.732 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.553 ±(99.9%) 0.008 ms/op
Iteration   1: 3.543 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.976 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.588 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  9.638 ms/op
                 existUser·p0.9999: 15.285 ms/op
                 existUser·p1.00:   15.532 ms/op

Iteration   2: 3.529 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.756 ms/op
                 existUser·p0.50:   3.478 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.547 ms/op
                 existUser·p0.99:   6.005 ms/op
                 existUser·p0.999:  12.170 ms/op
                 existUser·p0.9999: 17.332 ms/op
                 existUser·p1.00:   18.383 ms/op

Iteration   3: 3.581 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.692 ms/op
                 existUser·p0.50:   3.498 ms/op
                 existUser·p0.90:   4.190 ms/op
                 existUser·p0.95:   4.571 ms/op
                 existUser·p0.99:   6.201 ms/op
                 existUser·p0.999:  10.856 ms/op
                 existUser·p0.9999: 18.745 ms/op
                 existUser·p1.00:   18.809 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 270304
  mean =      3.551 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 401 
    [ 1.250,  2.500) = 8502 
    [ 2.500,  3.750) = 189119 
    [ 3.750,  5.000) = 64691 
    [ 5.000,  6.250) = 5271 
    [ 6.250,  7.500) = 1418 
    [ 7.500,  8.750) = 432 
    [ 8.750, 10.000) = 149 
    [10.000, 11.250) = 126 
    [11.250, 12.500) = 57 
    [12.500, 13.750) = 21 
    [13.750, 15.000) = 36 
    [15.000, 16.250) = 33 
    [16.250, 17.500) = 24 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.692 ms/op
     p(50.0000) =      3.486 ms/op
     p(90.0000) =      4.170 ms/op
     p(95.0000) =      4.571 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     10.584 ms/op
     p(99.9900) =     17.433 ms/op
     p(99.9990) =     18.776 ms/op
     p(99.9999) =     18.809 ms/op
    p(100.0000) =     18.809 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 5.824 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 3.943 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.852 ±(99.9%) 0.010 ms/op
Iteration   1: 3.715 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.763 ms/op
                 getUser·p0.50:   3.641 ms/op
                 getUser·p0.90:   4.391 ms/op
                 getUser·p0.95:   4.882 ms/op
                 getUser·p0.99:   6.529 ms/op
                 getUser·p0.999:  11.954 ms/op
                 getUser·p0.9999: 14.470 ms/op
                 getUser·p1.00:   14.696 ms/op

Iteration   2: 3.724 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.666 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.841 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  9.552 ms/op
                 getUser·p0.9999: 16.810 ms/op
                 getUser·p1.00:   20.709 ms/op

Iteration   3: 3.688 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.028 ms/op
                 getUser·p0.50:   3.633 ms/op
                 getUser·p0.90:   4.407 ms/op
                 getUser·p0.95:   4.776 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  12.229 ms/op
                 getUser·p0.9999: 19.966 ms/op
                 getUser·p1.00:   20.316 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 258886
  mean =      3.709 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9821 
    [ 2.500,  5.000) = 239066 
    [ 5.000,  7.500) = 8769 
    [ 7.500, 10.000) = 958 
    [10.000, 12.500) = 86 
    [12.500, 15.000) = 75 
    [15.000, 17.500) = 56 
    [17.500, 20.000) = 47 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.763 ms/op
     p(50.0000) =      3.645 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.833 ms/op
     p(99.0000) =      6.398 ms/op
     p(99.9000) =     10.144 ms/op
     p(99.9900) =     19.468 ms/op
     p(99.9990) =     20.258 ms/op
     p(99.9999) =     20.709 ms/op
    p(100.0000) =     20.709 ms/op


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
# Warmup Iteration   1: 5.618 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 5.198 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.906 ±(99.9%) 0.016 ms/op
Iteration   1: 4.866 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.800 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   6.382 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   9.026 ms/op
                 listUser·p0.999:  15.488 ms/op
                 listUser·p0.9999: 17.821 ms/op
                 listUser·p1.00:   18.219 ms/op

Iteration   2: 4.854 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.405 ms/op
                 listUser·p0.50:   4.588 ms/op
                 listUser·p0.90:   6.390 ms/op
                 listUser·p0.95:   7.356 ms/op
                 listUser·p0.99:   9.388 ms/op
                 listUser·p0.999:  17.305 ms/op
                 listUser·p0.9999: 20.152 ms/op
                 listUser·p1.00:   20.775 ms/op

Iteration   3: 4.761 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.067 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.726 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.949 ms/op
                 listUser·p0.999:  19.780 ms/op
                 listUser·p0.9999: 22.024 ms/op
                 listUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198790
  mean =      4.827 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 537 
    [ 2.500,  5.000) = 144794 
    [ 5.000,  7.500) = 45924 
    [ 7.500, 10.000) = 6388 
    [10.000, 12.500) = 678 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 143 
    [17.500, 20.000) = 130 
    [20.000, 22.500) = 59 
    [22.500, 25.000) = 3 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.067 ms/op
     p(50.0000) =      4.596 ms/op
     p(90.0000) =      6.201 ms/op
     p(95.0000) =      7.176 ms/op
     p(99.0000) =      9.126 ms/op
     p(99.9000) =     17.439 ms/op
     p(99.9900) =     21.561 ms/op
     p(99.9990) =     22.879 ms/op
     p(99.9999) =     23.429 ms/op
    p(100.0000) =     23.429 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.620 ± 2.922  ops/ms
ClientGrpc.existUser                       thrpt       3   9.126 ± 4.178  ops/ms
ClientGrpc.getUser                         thrpt       3   8.585 ± 0.353  ops/ms
ClientGrpc.listUser                        thrpt       3   6.682 ± 0.926  ops/ms
ClientGrpc.createUser                       avgt       3   3.769 ± 0.513   ms/op
ClientGrpc.existUser                        avgt       3   3.528 ± 0.159   ms/op
ClientGrpc.getUser                          avgt       3   3.741 ± 1.341   ms/op
ClientGrpc.listUser                         avgt       3   4.835 ± 3.999   ms/op
ClientGrpc.createUser                     sample  260245   3.685 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.856           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.621           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.432           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.850           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.406           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.321           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.945           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.546           ms/op
ClientGrpc.existUser                      sample  270304   3.551 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.692           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.486           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.170           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.571           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.062           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.584           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.433           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.809           ms/op
ClientGrpc.getUser                        sample  258886   3.709 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.763           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.645           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.432           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.833           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.398           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.144           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.468           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.709           ms/op
ClientGrpc.listUser                       sample  198790   4.827 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.067           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.596           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.201           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.176           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.126           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.439           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.561           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.429           ms/op
