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
# Warmup Iteration   1: 3.011 ops/ms
# Warmup Iteration   2: 6.748 ops/ms
# Warmup Iteration   3: 8.082 ops/ms
Iteration   1: 8.232 ops/ms
Iteration   2: 8.370 ops/ms
Iteration   3: 8.452 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.351 ±(99.9%) 2.028 ops/ms [Average]
  (min, avg, max) = (8.232, 8.351, 8.452), stdev = 0.111
  CI (99.9%): [6.323, 10.379] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 5.444 ops/ms
# Warmup Iteration   2: 8.231 ops/ms
# Warmup Iteration   3: 8.785 ops/ms
Iteration   1: 8.956 ops/ms
Iteration   2: 8.930 ops/ms
Iteration   3: 8.775 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.887 ±(99.9%) 1.791 ops/ms [Average]
  (min, avg, max) = (8.775, 8.887, 8.956), stdev = 0.098
  CI (99.9%): [7.096, 10.678] (assumes normal distribution)


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
# Warmup Iteration   1: 5.377 ops/ms
# Warmup Iteration   2: 7.883 ops/ms
# Warmup Iteration   3: 8.247 ops/ms
Iteration   1: 8.302 ops/ms
Iteration   2: 8.313 ops/ms
Iteration   3: 8.488 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.368 ±(99.9%) 1.907 ops/ms [Average]
  (min, avg, max) = (8.302, 8.368, 8.488), stdev = 0.105
  CI (99.9%): [6.461, 10.275] (assumes normal distribution)


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
# Warmup Iteration   1: 4.069 ops/ms
# Warmup Iteration   2: 6.152 ops/ms
# Warmup Iteration   3: 6.470 ops/ms
Iteration   1: 6.675 ops/ms
Iteration   2: 6.583 ops/ms
Iteration   3: 6.680 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.646 ±(99.9%) 0.987 ops/ms [Average]
  (min, avg, max) = (6.583, 6.646, 6.680), stdev = 0.054
  CI (99.9%): [5.659, 7.633] (assumes normal distribution)


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
# Warmup Iteration   1: 5.092 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.942 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.831 ±(99.9%) 0.006 ms/op
Iteration   1: 3.822 ±(99.9%) 0.015 ms/op
Iteration   2: 3.819 ±(99.9%) 0.007 ms/op
Iteration   3: 3.869 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.837 ±(99.9%) 0.514 ms/op [Average]
  (min, avg, max) = (3.819, 3.837, 3.869), stdev = 0.028
  CI (99.9%): [3.323, 4.350] (assumes normal distribution)


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
# Warmup Iteration   1: 5.225 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.917 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.730 ±(99.9%) 0.003 ms/op
Iteration   1: 3.637 ±(99.9%) 0.003 ms/op
Iteration   2: 3.565 ±(99.9%) 0.003 ms/op
Iteration   3: 3.598 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.600 ±(99.9%) 0.655 ms/op [Average]
  (min, avg, max) = (3.565, 3.600, 3.637), stdev = 0.036
  CI (99.9%): [2.945, 4.255] (assumes normal distribution)


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
# Warmup Iteration   1: 5.629 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.991 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.820 ±(99.9%) 0.004 ms/op
Iteration   1: 3.704 ±(99.9%) 0.005 ms/op
Iteration   2: 3.817 ±(99.9%) 0.003 ms/op
Iteration   3: 3.798 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.773 ±(99.9%) 1.106 ms/op [Average]
  (min, avg, max) = (3.704, 3.773, 3.817), stdev = 0.061
  CI (99.9%): [2.667, 4.879] (assumes normal distribution)


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
# Warmup Iteration   1: 6.996 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 5.212 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.935 ±(99.9%) 0.022 ms/op
Iteration   1: 4.826 ±(99.9%) 0.019 ms/op
Iteration   2: 4.899 ±(99.9%) 0.011 ms/op
Iteration   3: 4.884 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.870 ±(99.9%) 0.700 ms/op [Average]
  (min, avg, max) = (4.826, 4.870, 4.899), stdev = 0.038
  CI (99.9%): [4.170, 5.570] (assumes normal distribution)


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
# Warmup Iteration   1: 5.448 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 4.084 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.009 ms/op
Iteration   1: 3.821 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.804 ms/op
                 createUser·p0.50:   3.748 ms/op
                 createUser·p0.90:   4.530 ms/op
                 createUser·p0.95:   4.891 ms/op
                 createUser·p0.99:   6.463 ms/op
                 createUser·p0.999:  9.029 ms/op
                 createUser·p0.9999: 16.696 ms/op
                 createUser·p1.00:   17.105 ms/op

Iteration   2: 3.785 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.823 ms/op
                 createUser·p0.50:   3.707 ms/op
                 createUser·p0.90:   4.440 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.679 ms/op
                 createUser·p0.999:  11.567 ms/op
                 createUser·p0.9999: 16.286 ms/op
                 createUser·p1.00:   16.531 ms/op

Iteration   3: 3.743 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.930 ms/op
                 createUser·p0.50:   3.674 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.620 ms/op
                 createUser·p0.99:   5.931 ms/op
                 createUser·p0.999:  8.602 ms/op
                 createUser·p0.9999: 19.723 ms/op
                 createUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 253799
  mean =      3.783 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3998 
    [ 2.500,  5.000) = 241104 
    [ 5.000,  7.500) = 7521 
    [ 7.500, 10.000) = 897 
    [10.000, 12.500) = 104 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 75 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.804 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.776 ms/op
     p(99.0000) =      6.324 ms/op
     p(99.9000) =     10.256 ms/op
     p(99.9900) =     19.407 ms/op
     p(99.9990) =     19.968 ms/op
     p(99.9999) =     20.120 ms/op
    p(100.0000) =     20.120 ms/op


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
# Warmup Iteration   1: 5.131 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.837 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.611 ±(99.9%) 0.008 ms/op
Iteration   1: 3.659 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.600 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.267 ms/op
                 existUser·p0.999:  12.156 ms/op
                 existUser·p0.9999: 16.810 ms/op
                 existUser·p1.00:   17.269 ms/op

Iteration   2: 3.596 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.918 ms/op
                 existUser·p0.50:   3.555 ms/op
                 existUser·p0.90:   4.219 ms/op
                 existUser·p0.95:   4.522 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  8.915 ms/op
                 existUser·p0.9999: 26.677 ms/op
                 existUser·p1.00:   26.935 ms/op

Iteration   3: 3.647 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.991 ms/op
                 existUser·p0.50:   3.576 ms/op
                 existUser·p0.90:   4.448 ms/op
                 existUser·p0.95:   4.801 ms/op
                 existUser·p0.99:   6.022 ms/op
                 existUser·p0.999:  11.148 ms/op
                 existUser·p0.9999: 19.930 ms/op
                 existUser·p1.00:   20.414 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 264269
  mean =      3.634 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9671 
    [ 2.500,  5.000) = 247049 
    [ 5.000,  7.500) = 6568 
    [ 7.500, 10.000) = 705 
    [10.000, 12.500) = 55 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 7 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.918 ms/op
     p(50.0000) =      3.576 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      5.972 ms/op
     p(99.9000) =     10.763 ms/op
     p(99.9900) =     26.266 ms/op
     p(99.9990) =     26.860 ms/op
     p(99.9999) =     26.935 ms/op
    p(100.0000) =     26.935 ms/op


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
# Warmup Iteration   1: 5.751 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 4.020 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.896 ±(99.9%) 0.011 ms/op
Iteration   1: 3.856 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.961 ms/op
                 getUser·p0.50:   3.760 ms/op
                 getUser·p0.90:   4.596 ms/op
                 getUser·p0.95:   4.948 ms/op
                 getUser·p0.99:   6.570 ms/op
                 getUser·p0.999:  10.209 ms/op
                 getUser·p0.9999: 26.041 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   2: 3.815 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.739 ms/op
                 getUser·p0.50:   3.764 ms/op
                 getUser·p0.90:   4.637 ms/op
                 getUser·p0.95:   5.022 ms/op
                 getUser·p0.99:   6.324 ms/op
                 getUser·p0.999:  10.782 ms/op
                 getUser·p0.9999: 16.830 ms/op
                 getUser·p1.00:   17.564 ms/op

Iteration   3: 3.826 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.752 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.932 ms/op
                 getUser·p0.99:   6.218 ms/op
                 getUser·p0.999:  10.153 ms/op
                 getUser·p0.9999: 20.513 ms/op
                 getUser·p1.00:   20.775 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 250450
  mean =      3.832 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6622 
    [ 2.500,  5.000) = 231919 
    [ 5.000,  7.500) = 10647 
    [ 7.500, 10.000) = 983 
    [10.000, 12.500) = 145 
    [12.500, 15.000) = 17 
    [15.000, 17.500) = 52 
    [17.500, 20.000) = 16 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.739 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.588 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      6.373 ms/op
     p(99.9000) =     10.289 ms/op
     p(99.9900) =     25.525 ms/op
     p(99.9990) =     26.181 ms/op
     p(99.9999) =     26.280 ms/op
    p(100.0000) =     26.280 ms/op


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
# Warmup Iteration   1: 7.389 ±(99.9%) 0.078 ms/op
# Warmup Iteration   2: 4.989 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.950 ±(99.9%) 0.015 ms/op
Iteration   1: 4.888 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.464 ms/op
                 listUser·p0.50:   4.678 ms/op
                 listUser·p0.90:   6.136 ms/op
                 listUser·p0.95:   7.152 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  15.023 ms/op
                 listUser·p0.9999: 17.648 ms/op
                 listUser·p1.00:   19.366 ms/op

Iteration   2: 4.861 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.135 ms/op
                 listUser·p0.50:   4.637 ms/op
                 listUser·p0.90:   6.103 ms/op
                 listUser·p0.95:   6.791 ms/op
                 listUser·p0.99:   8.716 ms/op
                 listUser·p0.999:  17.373 ms/op
                 listUser·p0.9999: 20.513 ms/op
                 listUser·p1.00:   22.381 ms/op

Iteration   3: 4.810 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   0.818 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.857 ms/op
                 listUser·p0.95:   6.742 ms/op
                 listUser·p0.99:   8.618 ms/op
                 listUser·p0.999:  19.071 ms/op
                 listUser·p0.9999: 21.300 ms/op
                 listUser·p1.00:   22.086 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198023
  mean =      4.853 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 222 
    [ 2.500,  5.000) = 142042 
    [ 5.000,  7.500) = 49708 
    [ 7.500, 10.000) = 5161 
    [10.000, 12.500) = 582 
    [12.500, 15.000) = 52 
    [15.000, 17.500) = 97 
    [17.500, 20.000) = 107 
    [20.000, 22.500) = 52 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.818 ms/op
     p(50.0000) =      4.645 ms/op
     p(90.0000) =      6.046 ms/op
     p(95.0000) =      6.906 ms/op
     p(99.0000) =      8.667 ms/op
     p(99.9000) =     16.384 ms/op
     p(99.9900) =     20.847 ms/op
     p(99.9990) =     22.252 ms/op
     p(99.9999) =     22.381 ms/op
    p(100.0000) =     22.381 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.351 ± 2.028  ops/ms
ClientGrpc.existUser                       thrpt       3   8.887 ± 1.791  ops/ms
ClientGrpc.getUser                         thrpt       3   8.368 ± 1.907  ops/ms
ClientGrpc.listUser                        thrpt       3   6.646 ± 0.987  ops/ms
ClientGrpc.createUser                       avgt       3   3.837 ± 0.514   ms/op
ClientGrpc.existUser                        avgt       3   3.600 ± 0.655   ms/op
ClientGrpc.getUser                          avgt       3   3.773 ± 1.106   ms/op
ClientGrpc.listUser                         avgt       3   4.870 ± 0.700   ms/op
ClientGrpc.createUser                     sample  253799   3.783 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.804           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.711           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.424           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.776           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.324           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.256           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          19.407           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          20.120           ms/op
ClientGrpc.existUser                      sample  264269   3.634 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.918           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.576           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.317           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.686           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.972           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.763           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          26.266           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.935           ms/op
ClientGrpc.getUser                        sample  250450   3.832 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.739           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.760           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.588           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.973           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.373           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          10.289           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          25.525           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          26.280           ms/op
ClientGrpc.listUser                       sample  198023   4.853 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.818           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.645           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.046           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.906           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.667           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.384           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.847           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.381           ms/op
