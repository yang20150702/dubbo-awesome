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
# Warmup Iteration   1: 2.999 ops/ms
# Warmup Iteration   2: 6.869 ops/ms
# Warmup Iteration   3: 8.135 ops/ms
Iteration   1: 7.987 ops/ms
Iteration   2: 8.406 ops/ms
Iteration   3: 8.441 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.278 ±(99.9%) 4.608 ops/ms [Average]
  (min, avg, max) = (7.987, 8.278, 8.441), stdev = 0.253
  CI (99.9%): [3.670, 12.887] (assumes normal distribution)


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
# Warmup Iteration   1: 5.480 ops/ms
# Warmup Iteration   2: 8.262 ops/ms
# Warmup Iteration   3: 8.683 ops/ms
Iteration   1: 9.077 ops/ms
Iteration   2: 8.526 ops/ms
Iteration   3: 9.001 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.868 ±(99.9%) 5.443 ops/ms [Average]
  (min, avg, max) = (8.526, 8.868, 9.077), stdev = 0.298
  CI (99.9%): [3.425, 14.311] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:58
# Fork: 1 of 1
# Warmup Iteration   1: 5.005 ops/ms
# Warmup Iteration   2: 7.927 ops/ms
# Warmup Iteration   3: 7.826 ops/ms
Iteration   1: 8.247 ops/ms
Iteration   2: 7.942 ops/ms
Iteration   3: 8.389 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.193 ±(99.9%) 4.164 ops/ms [Average]
  (min, avg, max) = (7.942, 8.193, 8.389), stdev = 0.228
  CI (99.9%): [4.029, 12.356] (assumes normal distribution)


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
# Warmup Iteration   1: 4.155 ops/ms
# Warmup Iteration   2: 5.874 ops/ms
# Warmup Iteration   3: 6.406 ops/ms
Iteration   1: 6.542 ops/ms
Iteration   2: 6.502 ops/ms
Iteration   3: 6.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.534 ±(99.9%) 0.513 ops/ms [Average]
  (min, avg, max) = (6.502, 6.534, 6.557), stdev = 0.028
  CI (99.9%): [6.021, 7.046] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 5.343 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.055 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.013 ms/op
Iteration   1: 3.920 ±(99.9%) 0.004 ms/op
Iteration   2: 3.813 ±(99.9%) 0.002 ms/op
Iteration   3: 3.684 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.806 ±(99.9%) 2.155 ms/op [Average]
  (min, avg, max) = (3.684, 3.806, 3.920), stdev = 0.118
  CI (99.9%): [1.650, 5.961] (assumes normal distribution)


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
# Warmup Iteration   1: 5.077 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.690 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.516 ±(99.9%) 0.004 ms/op
Iteration   1: 3.758 ±(99.9%) 0.003 ms/op
Iteration   2: 3.571 ±(99.9%) 0.003 ms/op
Iteration   3: 3.496 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.608 ±(99.9%) 2.461 ms/op [Average]
  (min, avg, max) = (3.496, 3.608, 3.758), stdev = 0.135
  CI (99.9%): [1.147, 6.069] (assumes normal distribution)


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
# Warmup Iteration   1: 5.659 ±(99.9%) 0.024 ms/op
# Warmup Iteration   2: 4.104 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.900 ±(99.9%) 0.004 ms/op
Iteration   1: 3.899 ±(99.9%) 0.003 ms/op
Iteration   2: 3.754 ±(99.9%) 0.004 ms/op
Iteration   3: 3.758 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.804 ±(99.9%) 1.500 ms/op [Average]
  (min, avg, max) = (3.754, 3.804, 3.899), stdev = 0.082
  CI (99.9%): [2.304, 5.304] (assumes normal distribution)


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
# Warmup Iteration   1: 7.697 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.076 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.696 ±(99.9%) 0.015 ms/op
Iteration   1: 4.914 ±(99.9%) 0.013 ms/op
Iteration   2: 4.822 ±(99.9%) 0.012 ms/op
Iteration   3: 4.753 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.830 ±(99.9%) 1.475 ms/op [Average]
  (min, avg, max) = (4.753, 4.830, 4.914), stdev = 0.081
  CI (99.9%): [3.355, 6.304] (assumes normal distribution)


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
# Warmup Iteration   1: 5.508 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 4.008 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.832 ±(99.9%) 0.010 ms/op
Iteration   1: 3.800 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.952 ms/op
                 createUser·p0.50:   3.670 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.161 ms/op
                 createUser·p0.99:   6.930 ms/op
                 createUser·p0.999:  13.958 ms/op
                 createUser·p0.9999: 16.075 ms/op
                 createUser·p1.00:   16.531 ms/op

Iteration   2: 3.712 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.998 ms/op
                 createUser·p0.50:   3.613 ms/op
                 createUser·p0.90:   4.284 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.883 ms/op
                 createUser·p0.999:  12.890 ms/op
                 createUser·p0.9999: 15.833 ms/op
                 createUser·p1.00:   16.400 ms/op

Iteration   3: 3.773 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.953 ms/op
                 createUser·p0.50:   3.690 ms/op
                 createUser·p0.90:   4.596 ms/op
                 createUser·p0.95:   4.923 ms/op
                 createUser·p0.99:   6.013 ms/op
                 createUser·p0.999:  10.519 ms/op
                 createUser·p0.9999: 20.492 ms/op
                 createUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 255302
  mean =      3.761 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6320 
    [ 2.500,  5.000) = 236782 
    [ 5.000,  7.500) = 10603 
    [ 7.500, 10.000) = 1138 
    [10.000, 12.500) = 193 
    [12.500, 15.000) = 115 
    [15.000, 17.500) = 91 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 15 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.952 ms/op
     p(50.0000) =      3.654 ms/op
     p(90.0000) =      4.547 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.644 ms/op
     p(99.9000) =     12.665 ms/op
     p(99.9900) =     19.726 ms/op
     p(99.9990) =     21.507 ms/op
     p(99.9999) =     21.627 ms/op
    p(100.0000) =     21.627 ms/op


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
# Warmup Iteration   1: 5.110 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.808 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.007 ms/op
Iteration   1: 3.490 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.910 ms/op
                 existUser·p0.50:   3.437 ms/op
                 existUser·p0.90:   4.026 ms/op
                 existUser·p0.95:   4.375 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  9.083 ms/op
                 existUser·p0.9999: 15.712 ms/op
                 existUser·p1.00:   15.892 ms/op

Iteration   2: 3.540 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.061 ms/op
                 existUser·p0.50:   3.486 ms/op
                 existUser·p0.90:   4.051 ms/op
                 existUser·p0.95:   4.366 ms/op
                 existUser·p0.99:   5.758 ms/op
                 existUser·p0.999:  12.081 ms/op
                 existUser·p0.9999: 17.170 ms/op
                 existUser·p1.00:   18.219 ms/op

Iteration   3: 3.701 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.880 ms/op
                 existUser·p0.50:   3.609 ms/op
                 existUser·p0.90:   4.530 ms/op
                 existUser·p0.95:   4.956 ms/op
                 existUser·p0.99:   6.673 ms/op
                 existUser·p0.999:  10.069 ms/op
                 existUser·p0.9999: 20.262 ms/op
                 existUser·p1.00:   20.611 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 268386
  mean =      3.575 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7771 
    [ 2.500,  5.000) = 253185 
    [ 5.000,  7.500) = 6407 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 133 
    [12.500, 15.000) = 95 
    [15.000, 17.500) = 51 
    [17.500, 20.000) = 26 
    [20.000, 22.500) = 13 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.880 ms/op
     p(50.0000) =      3.498 ms/op
     p(90.0000) =      4.227 ms/op
     p(95.0000) =      4.617 ms/op
     p(99.0000) =      5.931 ms/op
     p(99.9000) =     10.863 ms/op
     p(99.9900) =     19.442 ms/op
     p(99.9990) =     20.533 ms/op
     p(99.9999) =     20.611 ms/op
    p(100.0000) =     20.611 ms/op


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
# Warmup Iteration   1: 5.407 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 3.887 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.889 ±(99.9%) 0.009 ms/op
Iteration   1: 3.859 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.198 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.735 ms/op
                 getUser·p0.95:   5.284 ms/op
                 getUser·p0.99:   7.315 ms/op
                 getUser·p0.999:  10.118 ms/op
                 getUser·p0.9999: 15.361 ms/op
                 getUser·p1.00:   15.614 ms/op

Iteration   2: 3.807 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.174 ms/op
                 getUser·p0.50:   3.711 ms/op
                 getUser·p0.90:   4.489 ms/op
                 getUser·p0.95:   4.858 ms/op
                 getUser·p0.99:   6.136 ms/op
                 getUser·p0.999:  12.911 ms/op
                 getUser·p0.9999: 15.925 ms/op
                 getUser·p1.00:   17.236 ms/op

Iteration   3: 3.903 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.000 ms/op
                 getUser·p0.50:   3.805 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   6.478 ms/op
                 getUser·p0.999:  9.767 ms/op
                 getUser·p0.9999: 18.606 ms/op
                 getUser·p1.00:   19.988 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 248774
  mean =      3.856 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 22 
    [ 1.250,  2.500) = 4797 
    [ 2.500,  3.750) = 119856 
    [ 3.750,  5.000) = 110186 
    [ 5.000,  6.250) = 10351 
    [ 6.250,  7.500) = 2168 
    [ 7.500,  8.750) = 879 
    [ 8.750, 10.000) = 242 
    [10.000, 11.250) = 49 
    [11.250, 12.500) = 64 
    [12.500, 13.750) = 35 
    [13.750, 15.000) = 59 
    [15.000, 16.250) = 27 
    [16.250, 17.500) = 15 
    [17.500, 18.750) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.000 ms/op
     p(50.0000) =      3.748 ms/op
     p(90.0000) =      4.637 ms/op
     p(95.0000) =      5.079 ms/op
     p(99.0000) =      6.742 ms/op
     p(99.9000) =     10.227 ms/op
     p(99.9900) =     17.449 ms/op
     p(99.9990) =     19.826 ms/op
     p(99.9999) =     19.988 ms/op
    p(100.0000) =     19.988 ms/op


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
# Warmup Iteration   1: 6.544 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.453 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 5.076 ±(99.9%) 0.019 ms/op
Iteration   1: 4.916 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.372 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.455 ms/op
                 listUser·p0.95:   7.266 ms/op
                 listUser·p0.99:   9.363 ms/op
                 listUser·p0.999:  16.660 ms/op
                 listUser·p0.9999: 19.676 ms/op
                 listUser·p1.00:   24.445 ms/op

Iteration   2: 4.852 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.384 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   6.087 ms/op
                 listUser·p0.95:   7.062 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  18.612 ms/op
                 listUser·p0.9999: 23.685 ms/op
                 listUser·p1.00:   25.231 ms/op

Iteration   3: 4.709 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.186 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.792 ms/op
                 listUser·p0.95:   6.808 ms/op
                 listUser·p0.99:   9.302 ms/op
                 listUser·p0.999:  21.037 ms/op
                 listUser·p0.9999: 26.490 ms/op
                 listUser·p1.00:   27.132 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198965
  mean =      4.824 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 224 
    [ 2.500,  5.000) = 146253 
    [ 5.000,  7.500) = 45487 
    [ 7.500, 10.000) = 5796 
    [10.000, 12.500) = 689 
    [12.500, 15.000) = 120 
    [15.000, 17.500) = 134 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 14 

  Percentiles, ms/op:
      p(0.0000) =      1.186 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      6.136 ms/op
     p(95.0000) =      7.062 ms/op
     p(99.0000) =      9.224 ms/op
     p(99.9000) =     19.039 ms/op
     p(99.9900) =     24.324 ms/op
     p(99.9990) =     27.099 ms/op
     p(99.9999) =     27.132 ms/op
    p(100.0000) =     27.132 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.278 ± 4.608  ops/ms
ClientGrpc.existUser                       thrpt       3   8.868 ± 5.443  ops/ms
ClientGrpc.getUser                         thrpt       3   8.193 ± 4.164  ops/ms
ClientGrpc.listUser                        thrpt       3   6.534 ± 0.513  ops/ms
ClientGrpc.createUser                       avgt       3   3.806 ± 2.155   ms/op
ClientGrpc.existUser                        avgt       3   3.608 ± 2.461   ms/op
ClientGrpc.getUser                          avgt       3   3.804 ± 1.500   ms/op
ClientGrpc.listUser                         avgt       3   4.830 ± 1.475   ms/op
ClientGrpc.createUser                     sample  255302   3.761 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.952           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.654           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.547           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.973           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.644           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.665           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.726           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          21.627           ms/op
ClientGrpc.existUser                      sample  268386   3.575 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.880           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.498           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.227           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.617           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.931           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.863           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          19.442           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.611           ms/op
ClientGrpc.getUser                        sample  248774   3.856 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           1.000           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.748           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.637           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.079           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.742           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.227           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.449           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          19.988           ms/op
ClientGrpc.listUser                       sample  198965   4.824 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.186           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.571           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.136           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.062           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.224           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.039           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.324           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          27.132           ms/op
