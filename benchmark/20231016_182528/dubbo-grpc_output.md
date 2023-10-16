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
# Warmup Iteration   1: 3.152 ops/ms
# Warmup Iteration   2: 6.457 ops/ms
# Warmup Iteration   3: 8.153 ops/ms
Iteration   1: 8.195 ops/ms
Iteration   2: 8.461 ops/ms
Iteration   3: 8.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.515 ±(99.9%) 6.395 ops/ms [Average]
  (min, avg, max) = (8.195, 8.515, 8.890), stdev = 0.351
  CI (99.9%): [2.121, 14.910] (assumes normal distribution)


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
# Warmup Iteration   1: 5.912 ops/ms
# Warmup Iteration   2: 8.605 ops/ms
# Warmup Iteration   3: 8.772 ops/ms
Iteration   1: 8.808 ops/ms
Iteration   2: 8.892 ops/ms
Iteration   3: 8.961 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.887 ±(99.9%) 1.403 ops/ms [Average]
  (min, avg, max) = (8.808, 8.887, 8.961), stdev = 0.077
  CI (99.9%): [7.484, 10.290] (assumes normal distribution)


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
# Warmup Iteration   1: 5.528 ops/ms
# Warmup Iteration   2: 7.964 ops/ms
# Warmup Iteration   3: 8.306 ops/ms
Iteration   1: 8.334 ops/ms
Iteration   2: 8.458 ops/ms
Iteration   3: 8.207 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.333 ±(99.9%) 2.289 ops/ms [Average]
  (min, avg, max) = (8.207, 8.333, 8.458), stdev = 0.125
  CI (99.9%): [6.044, 10.622] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:50
# Fork: 1 of 1
# Warmup Iteration   1: 4.461 ops/ms
# Warmup Iteration   2: 6.291 ops/ms
# Warmup Iteration   3: 6.571 ops/ms
Iteration   1: 6.584 ops/ms
Iteration   2: 6.628 ops/ms
Iteration   3: 6.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.596 ±(99.9%) 0.526 ops/ms [Average]
  (min, avg, max) = (6.574, 6.596, 6.628), stdev = 0.029
  CI (99.9%): [6.070, 7.122] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 4.859 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 4.048 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 3.835 ±(99.9%) 0.004 ms/op
Iteration   1: 3.883 ±(99.9%) 0.003 ms/op
Iteration   2: 3.826 ±(99.9%) 0.002 ms/op
Iteration   3: 3.864 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.858 ±(99.9%) 0.527 ms/op [Average]
  (min, avg, max) = (3.826, 3.858, 3.883), stdev = 0.029
  CI (99.9%): [3.331, 4.384] (assumes normal distribution)


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
# Warmup Iteration   1: 5.142 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.786 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.526 ±(99.9%) 0.003 ms/op
Iteration   1: 3.585 ±(99.9%) 0.003 ms/op
Iteration   2: 3.497 ±(99.9%) 0.003 ms/op
Iteration   3: 3.669 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.584 ±(99.9%) 1.575 ms/op [Average]
  (min, avg, max) = (3.497, 3.584, 3.669), stdev = 0.086
  CI (99.9%): [2.008, 5.159] (assumes normal distribution)


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
# Warmup Iteration   1: 4.943 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.950 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.865 ±(99.9%) 0.003 ms/op
Iteration   1: 3.989 ±(99.9%) 0.003 ms/op
Iteration   2: 3.986 ±(99.9%) 0.003 ms/op
Iteration   3: 3.763 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.912 ±(99.9%) 2.368 ms/op [Average]
  (min, avg, max) = (3.763, 3.912, 3.989), stdev = 0.130
  CI (99.9%): [1.544, 6.281] (assumes normal distribution)


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
# Warmup Iteration   1: 5.780 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 5.302 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.872 ±(99.9%) 0.015 ms/op
Iteration   1: 4.747 ±(99.9%) 0.007 ms/op
Iteration   2: 4.875 ±(99.9%) 0.010 ms/op
Iteration   3: 4.869 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.830 ±(99.9%) 1.319 ms/op [Average]
  (min, avg, max) = (4.747, 4.830, 4.875), stdev = 0.072
  CI (99.9%): [3.512, 6.149] (assumes normal distribution)


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
# Warmup Iteration   1: 5.625 ±(99.9%) 0.063 ms/op
# Warmup Iteration   2: 4.151 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
Iteration   1: 3.872 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.839 ms/op
                 createUser·p0.50:   3.785 ms/op
                 createUser·p0.90:   4.620 ms/op
                 createUser·p0.95:   4.973 ms/op
                 createUser·p0.99:   6.447 ms/op
                 createUser·p0.999:  10.656 ms/op
                 createUser·p0.9999: 21.086 ms/op
                 createUser·p1.00:   21.430 ms/op

Iteration   2: 3.837 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.345 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.563 ms/op
                 createUser·p0.95:   4.866 ms/op
                 createUser·p0.99:   6.136 ms/op
                 createUser·p0.999:  10.281 ms/op
                 createUser·p0.9999: 20.679 ms/op
                 createUser·p1.00:   21.758 ms/op

Iteration   3: 3.722 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.720 ms/op
                 createUser·p0.50:   3.662 ms/op
                 createUser·p0.90:   4.465 ms/op
                 createUser·p0.95:   4.801 ms/op
                 createUser·p0.99:   6.078 ms/op
                 createUser·p0.999:  17.433 ms/op
                 createUser·p0.9999: 23.331 ms/op
                 createUser·p1.00:   23.757 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 252010
  mean =      3.809 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6313 
    [ 2.500,  5.000) = 235755 
    [ 5.000,  7.500) = 8652 
    [ 7.500, 10.000) = 898 
    [10.000, 12.500) = 170 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 41 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 46 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.345 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.555 ms/op
     p(95.0000) =      4.882 ms/op
     p(99.0000) =      6.210 ms/op
     p(99.9000) =     11.272 ms/op
     p(99.9900) =     23.003 ms/op
     p(99.9990) =     23.607 ms/op
     p(99.9999) =     23.757 ms/op
    p(100.0000) =     23.757 ms/op


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
# Warmup Iteration   1: 5.241 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 3.787 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.008 ms/op
Iteration   1: 3.664 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.943 ms/op
                 existUser·p0.50:   3.580 ms/op
                 existUser·p0.90:   4.342 ms/op
                 existUser·p0.95:   4.686 ms/op
                 existUser·p0.99:   6.218 ms/op
                 existUser·p0.999:  10.087 ms/op
                 existUser·p0.9999: 15.049 ms/op
                 existUser·p1.00:   15.335 ms/op

Iteration   2: 3.578 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.938 ms/op
                 existUser·p0.50:   3.518 ms/op
                 existUser·p0.90:   4.325 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  10.496 ms/op
                 existUser·p0.9999: 15.892 ms/op
                 existUser·p1.00:   16.318 ms/op

Iteration   3: 3.715 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.771 ms/op
                 existUser·p0.50:   3.625 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   4.669 ms/op
                 existUser·p0.99:   5.554 ms/op
                 existUser·p0.999:  8.561 ms/op
                 existUser·p0.9999: 18.235 ms/op
                 existUser·p1.00:   18.448 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 262888
  mean =      3.652 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 287 
    [ 1.250,  2.500) = 5960 
    [ 2.500,  3.750) = 161896 
    [ 3.750,  5.000) = 88070 
    [ 5.000,  6.250) = 4807 
    [ 6.250,  7.500) = 1044 
    [ 7.500,  8.750) = 406 
    [ 8.750, 10.000) = 153 
    [10.000, 11.250) = 59 
    [11.250, 12.500) = 8 
    [12.500, 13.750) = 44 
    [13.750, 15.000) = 61 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 49 
    [17.500, 18.750) = 12 

  Percentiles, ms/op:
      p(0.0000) =      0.771 ms/op
     p(50.0000) =      3.572 ms/op
     p(90.0000) =      4.407 ms/op
     p(95.0000) =      4.678 ms/op
     p(99.0000) =      5.800 ms/op
     p(99.9000) =     10.109 ms/op
     p(99.9900) =     16.908 ms/op
     p(99.9990) =     18.448 ms/op
     p(99.9999) =     18.448 ms/op
    p(100.0000) =     18.448 ms/op


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
# Warmup Iteration   1: 5.621 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.044 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.935 ±(99.9%) 0.009 ms/op
Iteration   1: 3.869 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.741 ms/op
                 getUser·p0.50:   3.777 ms/op
                 getUser·p0.90:   4.588 ms/op
                 getUser·p0.95:   4.973 ms/op
                 getUser·p0.99:   6.250 ms/op
                 getUser·p0.999:  9.416 ms/op
                 getUser·p0.9999: 15.605 ms/op
                 getUser·p1.00:   16.040 ms/op

Iteration   2: 3.952 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.620 ms/op
                 getUser·p0.50:   3.854 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.030 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.748 ms/op
                 getUser·p0.9999: 18.612 ms/op
                 getUser·p1.00:   19.333 ms/op

Iteration   3: 3.887 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.039 ms/op
                 getUser·p0.50:   3.801 ms/op
                 getUser·p0.90:   4.661 ms/op
                 getUser·p0.95:   4.907 ms/op
                 getUser·p0.99:   6.038 ms/op
                 getUser·p0.999:  8.995 ms/op
                 getUser·p0.9999: 20.218 ms/op
                 getUser·p1.00:   22.610 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 245932
  mean =      3.903 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1933 
    [ 2.500,  5.000) = 232538 
    [ 5.000,  7.500) = 10526 
    [ 7.500, 10.000) = 729 
    [10.000, 12.500) = 78 
    [12.500, 15.000) = 14 
    [15.000, 17.500) = 57 
    [17.500, 20.000) = 39 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.620 ms/op
     p(50.0000) =      3.809 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      4.964 ms/op
     p(99.0000) =      6.169 ms/op
     p(99.9000) =      9.650 ms/op
     p(99.9900) =     19.595 ms/op
     p(99.9990) =     21.740 ms/op
     p(99.9999) =     22.610 ms/op
    p(100.0000) =     22.610 ms/op


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
# Warmup Iteration   1: 6.323 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.286 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.991 ±(99.9%) 0.013 ms/op
Iteration   1: 4.826 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.839 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.702 ms/op
                 listUser·p0.95:   6.488 ms/op
                 listUser·p0.99:   8.454 ms/op
                 listUser·p0.999:  14.696 ms/op
                 listUser·p0.9999: 21.065 ms/op
                 listUser·p1.00:   21.398 ms/op

Iteration   2: 4.846 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.290 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.800 ms/op
                 listUser·p0.95:   6.627 ms/op
                 listUser·p0.99:   8.749 ms/op
                 listUser·p0.999:  16.352 ms/op
                 listUser·p0.9999: 19.445 ms/op
                 listUser·p1.00:   19.661 ms/op

Iteration   3: 4.836 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.106 ms/op
                 listUser·p0.50:   4.686 ms/op
                 listUser·p0.90:   5.669 ms/op
                 listUser·p0.95:   6.504 ms/op
                 listUser·p0.99:   8.335 ms/op
                 listUser·p0.999:  19.422 ms/op
                 listUser·p0.9999: 22.983 ms/op
                 listUser·p1.00:   23.986 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 198512
  mean =      4.836 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 219 
    [ 2.500,  5.000) = 142905 
    [ 5.000,  7.500) = 50637 
    [ 7.500, 10.000) = 4002 
    [10.000, 12.500) = 413 
    [12.500, 15.000) = 83 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 115 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.106 ms/op
     p(50.0000) =      4.686 ms/op
     p(90.0000) =      5.718 ms/op
     p(95.0000) =      6.545 ms/op
     p(99.0000) =      8.520 ms/op
     p(99.9000) =     16.990 ms/op
     p(99.9900) =     21.725 ms/op
     p(99.9990) =     23.857 ms/op
     p(99.9999) =     23.986 ms/op
    p(100.0000) =     23.986 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.515 ± 6.395  ops/ms
ClientGrpc.existUser                       thrpt       3   8.887 ± 1.403  ops/ms
ClientGrpc.getUser                         thrpt       3   8.333 ± 2.289  ops/ms
ClientGrpc.listUser                        thrpt       3   6.596 ± 0.526  ops/ms
ClientGrpc.createUser                       avgt       3   3.858 ± 0.527   ms/op
ClientGrpc.existUser                        avgt       3   3.584 ± 1.575   ms/op
ClientGrpc.getUser                          avgt       3   3.912 ± 2.368   ms/op
ClientGrpc.listUser                         avgt       3   4.830 ± 1.319   ms/op
ClientGrpc.createUser                     sample  252010   3.809 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.345           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.723           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.555           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.882           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.210           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          11.272           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          23.003           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.757           ms/op
ClientGrpc.existUser                      sample  262888   3.652 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.771           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.572           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.407           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.678           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.800           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.109           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.908           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          18.448           ms/op
ClientGrpc.getUser                        sample  245932   3.903 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.620           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.809           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.653           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.964           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.169           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           9.650           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          19.595           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          22.610           ms/op
ClientGrpc.listUser                       sample  198512   4.836 ± 0.008   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.106           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.686           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           5.718           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.545           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.520           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          16.990           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          21.725           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          23.986           ms/op
