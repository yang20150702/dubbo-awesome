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
# Warmup Iteration   1: 2.855 ops/ms
# Warmup Iteration   2: 6.557 ops/ms
# Warmup Iteration   3: 8.321 ops/ms
Iteration   1: 8.407 ops/ms
Iteration   2: 8.493 ops/ms
Iteration   3: 8.468 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.456 ±(99.9%) 0.804 ops/ms [Average]
  (min, avg, max) = (8.407, 8.456, 8.493), stdev = 0.044
  CI (99.9%): [7.652, 9.261] (assumes normal distribution)


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
# Warmup Iteration   1: 5.537 ops/ms
# Warmup Iteration   2: 8.503 ops/ms
# Warmup Iteration   3: 8.837 ops/ms
Iteration   1: 9.082 ops/ms
Iteration   2: 8.998 ops/ms
Iteration   3: 9.149 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.076 ±(99.9%) 1.381 ops/ms [Average]
  (min, avg, max) = (8.998, 9.076, 9.149), stdev = 0.076
  CI (99.9%): [7.696, 10.457] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 5.321 ops/ms
# Warmup Iteration   2: 7.995 ops/ms
# Warmup Iteration   3: 8.462 ops/ms
Iteration   1: 8.681 ops/ms
Iteration   2: 8.774 ops/ms
Iteration   3: 8.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.727 ±(99.9%) 0.850 ops/ms [Average]
  (min, avg, max) = (8.681, 8.727, 8.774), stdev = 0.047
  CI (99.9%): [7.878, 9.577] (assumes normal distribution)


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
# Warmup Iteration   1: 4.488 ops/ms
# Warmup Iteration   2: 6.030 ops/ms
# Warmup Iteration   3: 6.632 ops/ms
Iteration   1: 6.570 ops/ms
Iteration   2: 6.548 ops/ms
Iteration   3: 6.474 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.531 ±(99.9%) 0.915 ops/ms [Average]
  (min, avg, max) = (6.474, 6.531, 6.570), stdev = 0.050
  CI (99.9%): [5.616, 7.446] (assumes normal distribution)


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
# Warmup Iteration   1: 5.644 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.878 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.809 ±(99.9%) 0.007 ms/op
Iteration   1: 3.731 ±(99.9%) 0.004 ms/op
Iteration   2: 3.652 ±(99.9%) 0.019 ms/op
Iteration   3: 3.670 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.684 ±(99.9%) 0.762 ms/op [Average]
  (min, avg, max) = (3.652, 3.684, 3.731), stdev = 0.042
  CI (99.9%): [2.922, 4.447] (assumes normal distribution)


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
# Warmup Iteration   1: 4.871 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.699 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.002 ms/op
Iteration   1: 3.521 ±(99.9%) 0.004 ms/op
Iteration   2: 3.515 ±(99.9%) 0.005 ms/op
Iteration   3: 3.412 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.483 ±(99.9%) 1.120 ms/op [Average]
  (min, avg, max) = (3.412, 3.483, 3.521), stdev = 0.061
  CI (99.9%): [2.363, 4.603] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 5.036 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.925 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.744 ±(99.9%) 0.003 ms/op
Iteration   1: 3.737 ±(99.9%) 0.004 ms/op
Iteration   2: 3.717 ±(99.9%) 0.002 ms/op
Iteration   3: 3.680 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.711 ±(99.9%) 0.524 ms/op [Average]
  (min, avg, max) = (3.680, 3.711, 3.737), stdev = 0.029
  CI (99.9%): [3.188, 4.235] (assumes normal distribution)


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
# Warmup Iteration   1: 6.236 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 5.095 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.767 ±(99.9%) 0.030 ms/op
Iteration   1: 4.743 ±(99.9%) 0.013 ms/op
Iteration   2: 4.774 ±(99.9%) 0.017 ms/op
Iteration   3: 4.746 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.755 ±(99.9%) 0.314 ms/op [Average]
  (min, avg, max) = (4.743, 4.755, 4.774), stdev = 0.017
  CI (99.9%): [4.441, 5.068] (assumes normal distribution)


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
# Warmup Iteration   1: 5.759 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 3.982 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.009 ms/op
Iteration   1: 3.664 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.854 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.293 ms/op
                 createUser·p0.95:   4.686 ms/op
                 createUser·p0.99:   5.796 ms/op
                 createUser·p0.999:  11.506 ms/op
                 createUser·p0.9999: 15.025 ms/op
                 createUser·p1.00:   16.187 ms/op

Iteration   2: 3.626 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.768 ms/op
                 createUser·p0.50:   3.600 ms/op
                 createUser·p0.90:   4.243 ms/op
                 createUser·p0.95:   4.538 ms/op
                 createUser·p0.99:   5.784 ms/op
                 createUser·p0.999:  11.044 ms/op
                 createUser·p0.9999: 18.083 ms/op
                 createUser·p1.00:   19.202 ms/op

Iteration   3: 3.779 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.380 ms/op
                 createUser·p0.50:   3.682 ms/op
                 createUser·p0.90:   4.481 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   6.332 ms/op
                 createUser·p0.999:  14.876 ms/op
                 createUser·p0.9999: 21.565 ms/op
                 createUser·p1.00:   21.692 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 260078
  mean =      3.689 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6969 
    [ 2.500,  5.000) = 245832 
    [ 5.000,  7.500) = 6215 
    [ 7.500, 10.000) = 607 
    [10.000, 12.500) = 234 
    [12.500, 15.000) = 97 
    [15.000, 17.500) = 44 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.380 ms/op
     p(50.0000) =      3.629 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.694 ms/op
     p(99.0000) =      5.980 ms/op
     p(99.9000) =     11.829 ms/op
     p(99.9900) =     20.676 ms/op
     p(99.9990) =     21.692 ms/op
     p(99.9999) =     21.692 ms/op
    p(100.0000) =     21.692 ms/op


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
# Warmup Iteration   1: 5.223 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 3.751 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.549 ±(99.9%) 0.008 ms/op
Iteration   1: 3.570 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.972 ms/op
                 existUser·p0.50:   3.510 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   5.562 ms/op
                 existUser·p0.999:  10.195 ms/op
                 existUser·p0.9999: 21.661 ms/op
                 existUser·p1.00:   21.889 ms/op

Iteration   2: 3.570 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.994 ms/op
                 existUser·p0.50:   3.523 ms/op
                 existUser·p0.90:   4.243 ms/op
                 existUser·p0.95:   4.612 ms/op
                 existUser·p0.99:   5.759 ms/op
                 existUser·p0.999:  9.772 ms/op
                 existUser·p0.9999: 16.408 ms/op
                 existUser·p1.00:   16.810 ms/op

Iteration   3: 3.526 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.845 ms/op
                 existUser·p0.50:   3.482 ms/op
                 existUser·p0.90:   4.141 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  12.911 ms/op
                 existUser·p0.9999: 21.856 ms/op
                 existUser·p1.00:   22.282 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 269996
  mean =      3.555 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9626 
    [ 2.500,  5.000) = 254641 
    [ 5.000,  7.500) = 4793 
    [ 7.500, 10.000) = 643 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 53 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 50 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.845 ms/op
     p(50.0000) =      3.506 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.530 ms/op
     p(99.0000) =      5.702 ms/op
     p(99.9000) =     10.076 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     22.204 ms/op
     p(99.9999) =     22.282 ms/op
    p(100.0000) =     22.282 ms/op


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
# Warmup Iteration   1: 5.296 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.898 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.729 ±(99.9%) 0.009 ms/op
Iteration   1: 3.693 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.885 ms/op
                 getUser·p0.50:   3.621 ms/op
                 getUser·p0.90:   4.301 ms/op
                 getUser·p0.95:   4.645 ms/op
                 getUser·p0.99:   6.300 ms/op
                 getUser·p0.999:  12.088 ms/op
                 getUser·p0.9999: 19.945 ms/op
                 getUser·p1.00:   20.414 ms/op

Iteration   2: 3.611 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.910 ms/op
                 getUser·p0.50:   3.609 ms/op
                 getUser·p0.90:   4.309 ms/op
                 getUser·p0.95:   4.571 ms/op
                 getUser·p0.99:   5.530 ms/op
                 getUser·p0.999:  12.899 ms/op
                 getUser·p0.9999: 23.073 ms/op
                 getUser·p1.00:   24.183 ms/op

Iteration   3: 3.613 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.929 ms/op
                 getUser·p0.50:   3.564 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.530 ms/op
                 getUser·p0.99:   5.920 ms/op
                 getUser·p0.999:  12.678 ms/op
                 getUser·p0.9999: 24.412 ms/op
                 getUser·p1.00:   24.838 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263699
  mean =      3.639 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10243 
    [ 2.500,  5.000) = 246958 
    [ 5.000,  7.500) = 5315 
    [ 7.500, 10.000) = 702 
    [10.000, 12.500) = 217 
    [12.500, 15.000) = 103 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 54 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 87 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.885 ms/op
     p(50.0000) =      3.596 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.588 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     12.506 ms/op
     p(99.9900) =     24.117 ms/op
     p(99.9990) =     24.680 ms/op
     p(99.9999) =     24.838 ms/op
    p(100.0000) =     24.838 ms/op


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
# Warmup Iteration   1: 6.721 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.251 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.934 ±(99.9%) 0.014 ms/op
Iteration   1: 4.762 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.640 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.841 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  15.090 ms/op
                 listUser·p0.9999: 18.368 ms/op
                 listUser·p1.00:   18.547 ms/op

Iteration   2: 4.839 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.624 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.201 ms/op
                 listUser·p0.99:   9.077 ms/op
                 listUser·p0.999:  17.695 ms/op
                 listUser·p0.9999: 19.464 ms/op
                 listUser·p1.00:   21.955 ms/op

Iteration   3: 4.839 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.530 ms/op
                 listUser·p0.50:   4.661 ms/op
                 listUser·p0.90:   5.716 ms/op
                 listUser·p0.95:   7.029 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  20.173 ms/op
                 listUser·p0.9999: 34.800 ms/op
                 listUser·p1.00:   35.127 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 199476
  mean =      4.813 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 265 
    [ 2.500,  5.000) = 148488 
    [ 5.000,  7.500) = 44425 
    [ 7.500, 10.000) = 5276 
    [10.000, 12.500) = 597 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 129 
    [17.500, 20.000) = 121 
    [20.000, 22.500) = 19 
    [22.500, 25.000) = 14 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 4 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 31 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.530 ms/op
     p(50.0000) =      4.620 ms/op
     p(90.0000) =      5.956 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      8.782 ms/op
     p(99.9000) =     17.433 ms/op
     p(99.9900) =     34.148 ms/op
     p(99.9990) =     34.932 ms/op
     p(99.9999) =     35.127 ms/op
    p(100.0000) =     35.127 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.456 ± 0.804  ops/ms
ClientGrpc.existUser                       thrpt       3   9.076 ± 1.381  ops/ms
ClientGrpc.getUser                         thrpt       3   8.727 ± 0.850  ops/ms
ClientGrpc.listUser                        thrpt       3   6.531 ± 0.915  ops/ms
ClientGrpc.createUser                       avgt       3   3.684 ± 0.762   ms/op
ClientGrpc.existUser                        avgt       3   3.483 ± 1.120   ms/op
ClientGrpc.getUser                          avgt       3   3.711 ± 0.524   ms/op
ClientGrpc.listUser                         avgt       3   4.755 ± 0.314   ms/op
ClientGrpc.createUser                     sample  260078   3.689 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.380           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.629           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.342           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.694           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.980           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.829           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          20.676           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.692           ms/op
ClientGrpc.existUser                      sample  269996   3.555 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.845           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.506           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.182           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.530           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.702           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.076           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          21.627           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          22.282           ms/op
ClientGrpc.getUser                        sample  263699   3.639 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.885           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.596           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.260           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           5.939           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          12.506           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          24.117           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          24.838           ms/op
ClientGrpc.listUser                       sample  199476   4.813 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.530           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.620           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.956           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.021           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.782           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          17.433           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          34.148           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          35.127           ms/op
