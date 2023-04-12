# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.834 ops/ms
# Warmup Iteration   2: 9.517 ops/ms
# Warmup Iteration   3: 10.448 ops/ms
Iteration   1: 10.689 ops/ms
Iteration   2: 10.687 ops/ms
Iteration   3: 10.938 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.772 ±(99.9%) 2.633 ops/ms [Average]
  (min, avg, max) = (10.687, 10.772, 10.938), stdev = 0.144
  CI (99.9%): [8.139, 13.405] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 8.33% complete, ETA 00:11:57
# Fork: 1 of 1
# Warmup Iteration   1: 7.904 ops/ms
# Warmup Iteration   2: 11.020 ops/ms
# Warmup Iteration   3: 11.395 ops/ms
Iteration   1: 11.419 ops/ms
Iteration   2: 11.365 ops/ms
Iteration   3: 11.078 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  11.287 ±(99.9%) 3.344 ops/ms [Average]
  (min, avg, max) = (11.078, 11.287, 11.419), stdev = 0.183
  CI (99.9%): [7.943, 14.631] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 16.67% complete, ETA 00:10:51
# Fork: 1 of 1
# Warmup Iteration   1: 7.787 ops/ms
# Warmup Iteration   2: 10.668 ops/ms
# Warmup Iteration   3: 10.857 ops/ms
Iteration   1: 10.738 ops/ms
Iteration   2: 10.976 ops/ms
Iteration   3: 10.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.888 ±(99.9%) 2.387 ops/ms [Average]
  (min, avg, max) = (10.738, 10.888, 10.976), stdev = 0.131
  CI (99.9%): [8.501, 13.276] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 25.00% complete, ETA 00:09:45
# Fork: 1 of 1
# Warmup Iteration   1: 7.283 ops/ms
# Warmup Iteration   2: 8.187 ops/ms
# Warmup Iteration   3: 8.221 ops/ms
Iteration   1: 8.352 ops/ms
Iteration   2: 8.363 ops/ms
Iteration   3: 8.278 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.331 ±(99.9%) 0.843 ops/ms [Average]
  (min, avg, max) = (8.278, 8.331, 8.363), stdev = 0.046
  CI (99.9%): [7.488, 9.175] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.954 ±(99.9%) 0.011 ms/op
# Warmup Iteration   2: 3.055 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 2.938 ±(99.9%) 0.005 ms/op
Iteration   1: 2.959 ±(99.9%) 0.003 ms/op
Iteration   2: 2.918 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.944 ±(99.9%) 0.416 ms/op [Average]
  (min, avg, max) = (2.918, 2.944, 2.959), stdev = 0.023
  CI (99.9%): [2.528, 3.360] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.703 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.893 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.862 ±(99.9%) 0.003 ms/op
Iteration   1: 2.683 ±(99.9%) 0.004 ms/op
Iteration   2: 2.835 ±(99.9%) 0.002 ms/op
Iteration   3: 2.779 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.766 ±(99.9%) 1.406 ms/op [Average]
  (min, avg, max) = (2.683, 2.766, 2.835), stdev = 0.077
  CI (99.9%): [1.360, 4.171] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 3.945 ±(99.9%) 0.046 ms/op
# Warmup Iteration   2: 3.003 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.010 ±(99.9%) 0.004 ms/op
Iteration   1: 2.970 ±(99.9%) 0.002 ms/op
Iteration   2: 2.924 ±(99.9%) 0.003 ms/op
Iteration   3: 2.899 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  2.931 ±(99.9%) 0.665 ms/op [Average]
  (min, avg, max) = (2.899, 2.931, 2.970), stdev = 0.036
  CI (99.9%): [2.266, 3.596] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.737 ±(99.9%) 0.018 ms/op
# Warmup Iteration   2: 3.902 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.825 ±(99.9%) 0.017 ms/op
Iteration   1: 3.814 ±(99.9%) 0.052 ms/op
Iteration   2: 3.804 ±(99.9%) 0.055 ms/op
Iteration   3: 3.782 ±(99.9%) 0.026 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.800 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.782, 3.800, 3.814), stdev = 0.016
  CI (99.9%): [3.504, 4.096] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.createUser

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 3.987 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.158 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.044 ±(99.9%) 0.006 ms/op
Iteration   1: 2.950 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.814 ms/op
                 createUser·p0.50:   2.949 ms/op
                 createUser·p0.90:   3.342 ms/op
                 createUser·p0.95:   3.510 ms/op
                 createUser·p0.99:   4.243 ms/op
                 createUser·p0.999:  7.255 ms/op
                 createUser·p0.9999: 11.572 ms/op
                 createUser·p1.00:   12.648 ms/op

Iteration   2: 2.965 ±(99.9%) 0.005 ms/op
                 createUser·p0.00:   0.784 ms/op
                 createUser·p0.50:   2.974 ms/op
                 createUser·p0.90:   3.379 ms/op
                 createUser·p0.95:   3.588 ms/op
                 createUser·p0.99:   4.088 ms/op
                 createUser·p0.999:  6.095 ms/op
                 createUser·p0.9999: 12.091 ms/op
                 createUser·p1.00:   12.370 ms/op

Iteration   3: 3.050 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.686 ms/op
                 createUser·p0.50:   3.027 ms/op
                 createUser·p0.90:   3.568 ms/op
                 createUser·p0.95:   3.748 ms/op
                 createUser·p0.99:   4.317 ms/op
                 createUser·p0.999:  10.880 ms/op
                 createUser·p0.9999: 16.712 ms/op
                 createUser·p1.00:   16.712 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 321395
  mean =      2.988 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 1965 
    [ 1.250,  2.500) = 18211 
    [ 2.500,  3.750) = 290008 
    [ 3.750,  5.000) = 10083 
    [ 5.000,  6.250) = 673 
    [ 6.250,  7.500) = 102 
    [ 7.500,  8.750) = 90 
    [ 8.750, 10.000) = 6 
    [10.000, 11.250) = 57 
    [11.250, 12.500) = 100 
    [12.500, 13.750) = 29 
    [13.750, 15.000) = 57 
    [15.000, 16.250) = 0 
    [16.250, 17.500) = 14 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.686 ms/op
     p(50.0000) =      2.978 ms/op
     p(90.0000) =      3.449 ms/op
     p(95.0000) =      3.641 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      7.840 ms/op
     p(99.9900) =     14.189 ms/op
     p(99.9990) =     16.712 ms/op
     p(99.9999) =     16.712 ms/op
    p(100.0000) =     16.712 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.existUser

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.845 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 2.897 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.892 ±(99.9%) 0.005 ms/op
Iteration   1: 2.875 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.879 ms/op
                 existUser·p0.90:   3.207 ms/op
                 existUser·p0.95:   3.387 ms/op
                 existUser·p0.99:   4.141 ms/op
                 existUser·p0.999:  6.953 ms/op
                 existUser·p0.9999: 17.465 ms/op
                 existUser·p1.00:   17.695 ms/op

Iteration   2: 2.816 ±(99.9%) 0.005 ms/op
                 existUser·p0.00:   0.714 ms/op
                 existUser·p0.50:   2.834 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   4.243 ms/op
                 existUser·p0.999:  5.865 ms/op
                 existUser·p0.9999: 13.380 ms/op
                 existUser·p1.00:   13.861 ms/op

Iteration   3: 2.794 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.674 ms/op
                 existUser·p0.50:   2.830 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.506 ms/op
                 existUser·p0.99:   4.252 ms/op
                 existUser·p0.999:  7.748 ms/op
                 existUser·p0.9999: 24.710 ms/op
                 existUser·p1.00:   25.100 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 339556
  mean =      2.828 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 49384 
    [ 2.500,  5.000) = 289157 
    [ 5.000,  7.500) = 744 
    [ 7.500, 10.000) = 79 
    [10.000, 12.500) = 92 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.674 ms/op
     p(50.0000) =      2.851 ms/op
     p(90.0000) =      3.244 ms/op
     p(95.0000) =      3.457 ms/op
     p(99.0000) =      4.211 ms/op
     p(99.9000) =      6.892 ms/op
     p(99.9900) =     17.663 ms/op
     p(99.9990) =     25.002 ms/op
     p(99.9999) =     25.100 ms/op
    p(100.0000) =     25.100 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.getUser

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.061 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.053 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 2.991 ±(99.9%) 0.008 ms/op
Iteration   1: 3.014 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.645 ms/op
                 getUser·p0.50:   2.990 ms/op
                 getUser·p0.90:   3.514 ms/op
                 getUser·p0.95:   3.686 ms/op
                 getUser·p0.99:   4.530 ms/op
                 getUser·p0.999:  6.692 ms/op
                 getUser·p0.9999: 17.589 ms/op
                 getUser·p1.00:   17.695 ms/op

Iteration   2: 3.082 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.623 ms/op
                 getUser·p0.50:   3.068 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.715 ms/op
                 getUser·p0.99:   4.276 ms/op
                 getUser·p0.999:  7.733 ms/op
                 getUser·p0.9999: 19.759 ms/op
                 getUser·p1.00:   19.956 ms/op

Iteration   3: 2.939 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.691 ms/op
                 getUser·p0.50:   2.953 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.584 ms/op
                 getUser·p0.99:   4.194 ms/op
                 getUser·p0.999:  6.407 ms/op
                 getUser·p0.9999: 36.051 ms/op
                 getUser·p1.00:   36.438 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 319009
  mean =      3.011 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 24090 
    [ 2.500,  5.000) = 293758 
    [ 5.000,  7.500) = 899 
    [ 7.500, 10.000) = 62 
    [10.000, 12.500) = 8 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 83 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 32 

  Percentiles, ms/op:
      p(0.0000) =      0.623 ms/op
     p(50.0000) =      2.998 ms/op
     p(90.0000) =      3.535 ms/op
     p(95.0000) =      3.678 ms/op
     p(99.0000) =      4.309 ms/op
     p(99.9000) =      7.111 ms/op
     p(99.9900) =     35.324 ms/op
     p(99.9990) =     36.360 ms/op
     p(99.9999) =     36.438 ms/op
    p(100.0000) =     36.438 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-grpc_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientGrpc.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 4.901 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.799 ±(99.9%) 0.011 ms/op
Iteration   1: 3.851 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.872 ms/op
                 listUser·p0.50:   3.703 ms/op
                 listUser·p0.90:   4.891 ms/op
                 listUser·p0.95:   5.751 ms/op
                 listUser·p0.99:   6.849 ms/op
                 listUser·p0.999:  12.105 ms/op
                 listUser·p0.9999: 13.935 ms/op
                 listUser·p1.00:   14.385 ms/op

Iteration   2: 3.812 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.918 ms/op
                 listUser·p0.50:   3.690 ms/op
                 listUser·p0.90:   4.571 ms/op
                 listUser·p0.95:   5.128 ms/op
                 listUser·p0.99:   6.676 ms/op
                 listUser·p0.999:  13.766 ms/op
                 listUser·p0.9999: 21.818 ms/op
                 listUser·p1.00:   22.413 ms/op

Iteration   3: 3.797 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.879 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   4.735 ms/op
                 listUser·p0.95:   5.456 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.914 ms/op
                 listUser·p0.9999: 16.594 ms/op
                 listUser·p1.00:   17.957 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 251455
  mean =      3.820 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4559 
    [ 2.500,  5.000) = 227823 
    [ 5.000,  7.500) = 18001 
    [ 7.500, 10.000) = 609 
    [10.000, 12.500) = 149 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 20 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.872 ms/op
     p(50.0000) =      3.690 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.464 ms/op
     p(99.0000) =      6.717 ms/op
     p(99.9000) =     13.231 ms/op
     p(99.9900) =     20.503 ms/op
     p(99.9990) =     22.280 ms/op
     p(99.9999) =     22.413 ms/op
    p(100.0000) =     22.413 ms/op


# Run complete. Total time: 00:13:02

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.772 ± 2.633  ops/ms
ClientGrpc.existUser                       thrpt       3  11.287 ± 3.344  ops/ms
ClientGrpc.getUser                         thrpt       3  10.888 ± 2.387  ops/ms
ClientGrpc.listUser                        thrpt       3   8.331 ± 0.843  ops/ms
ClientGrpc.createUser                       avgt       3   2.944 ± 0.416   ms/op
ClientGrpc.existUser                        avgt       3   2.766 ± 1.406   ms/op
ClientGrpc.getUser                          avgt       3   2.931 ± 0.665   ms/op
ClientGrpc.listUser                         avgt       3   3.800 ± 0.296   ms/op
ClientGrpc.createUser                     sample  321395   2.988 ± 0.003   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.686           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           2.978           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.449           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.641           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.211           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.840           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.189           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          16.712           ms/op
ClientGrpc.existUser                      sample  339556   2.828 ± 0.003   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.674           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.851           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.244           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.457           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.211           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           6.892           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.663           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          25.100           ms/op
ClientGrpc.getUser                        sample  319009   3.011 ± 0.004   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.623           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           2.998           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.535           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.678           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.309           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           7.111           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          35.324           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          36.438           ms/op
ClientGrpc.listUser                       sample  251455   3.820 ± 0.006   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.872           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.690           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.719           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.464           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.717           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          13.231           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          20.503           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          22.413           ms/op
