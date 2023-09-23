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
# Warmup Iteration   1: 2.785 ops/ms
# Warmup Iteration   2: 6.409 ops/ms
# Warmup Iteration   3: 7.586 ops/ms
Iteration   1: 7.981 ops/ms
Iteration   2: 8.139 ops/ms
Iteration   3: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.114 ±(99.9%) 2.232 ops/ms [Average]
  (min, avg, max) = (7.981, 8.114, 8.222), stdev = 0.122
  CI (99.9%): [5.882, 10.346] (assumes normal distribution)


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
# Warmup Iteration   1: 5.445 ops/ms
# Warmup Iteration   2: 8.231 ops/ms
# Warmup Iteration   3: 8.498 ops/ms
Iteration   1: 8.609 ops/ms
Iteration   2: 8.833 ops/ms
Iteration   3: 8.643 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  8.695 ±(99.9%) 2.210 ops/ms [Average]
  (min, avg, max) = (8.609, 8.695, 8.833), stdev = 0.121
  CI (99.9%): [6.485, 10.905] (assumes normal distribution)


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
# Warmup Iteration   1: 5.022 ops/ms
# Warmup Iteration   2: 7.665 ops/ms
# Warmup Iteration   3: 7.810 ops/ms
Iteration   1: 8.153 ops/ms
Iteration   2: 8.220 ops/ms
Iteration   3: 8.361 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.245 ±(99.9%) 1.942 ops/ms [Average]
  (min, avg, max) = (8.153, 8.245, 8.361), stdev = 0.106
  CI (99.9%): [6.303, 10.187] (assumes normal distribution)


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
# Warmup Iteration   1: 3.929 ops/ms
# Warmup Iteration   2: 5.754 ops/ms
# Warmup Iteration   3: 6.311 ops/ms
Iteration   1: 6.312 ops/ms
Iteration   2: 5.768 ops/ms
Iteration   3: 5.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  5.961 ±(99.9%) 5.554 ops/ms [Average]
  (min, avg, max) = (5.768, 5.961, 6.312), stdev = 0.304
  CI (99.9%): [0.407, 11.515] (assumes normal distribution)


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
# Warmup Iteration   1: 6.304 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 4.356 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 4.198 ±(99.9%) 0.013 ms/op
Iteration   1: 4.085 ±(99.9%) 0.002 ms/op
Iteration   2: 4.041 ±(99.9%) 0.003 ms/op
Iteration   3: 4.148 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  4.091 ±(99.9%) 0.985 ms/op [Average]
  (min, avg, max) = (4.041, 4.091, 4.148), stdev = 0.054
  CI (99.9%): [3.106, 5.077] (assumes normal distribution)


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
# Warmup Iteration   1: 5.829 ±(99.9%) 0.026 ms/op
# Warmup Iteration   2: 4.034 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.714 ±(99.9%) 0.003 ms/op
Iteration   1: 3.674 ±(99.9%) 0.002 ms/op
Iteration   2: 3.547 ±(99.9%) 0.002 ms/op
Iteration   3: 3.557 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.593 ±(99.9%) 1.287 ms/op [Average]
  (min, avg, max) = (3.547, 3.593, 3.674), stdev = 0.071
  CI (99.9%): [2.306, 4.880] (assumes normal distribution)


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
# Warmup Iteration   1: 5.789 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 4.103 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.016 ±(99.9%) 0.005 ms/op
Iteration   1: 4.013 ±(99.9%) 0.002 ms/op
Iteration   2: 3.903 ±(99.9%) 0.003 ms/op
Iteration   3: 4.021 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.979 ±(99.9%) 1.194 ms/op [Average]
  (min, avg, max) = (3.903, 3.979, 4.021), stdev = 0.065
  CI (99.9%): [2.785, 5.173] (assumes normal distribution)


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
# Warmup Iteration   1: 7.497 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 5.230 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 5.027 ±(99.9%) 0.014 ms/op
Iteration   1: 4.951 ±(99.9%) 0.013 ms/op
Iteration   2: 4.934 ±(99.9%) 0.016 ms/op
Iteration   3: 5.014 ±(99.9%) 0.019 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.966 ±(99.9%) 0.766 ms/op [Average]
  (min, avg, max) = (4.934, 4.966, 5.014), stdev = 0.042
  CI (99.9%): [4.201, 5.732] (assumes normal distribution)


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
# Warmup Iteration   1: 5.921 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.270 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.040 ±(99.9%) 0.011 ms/op
Iteration   1: 3.802 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.033 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.686 ms/op
                 createUser·p0.95:   5.079 ms/op
                 createUser·p0.99:   6.357 ms/op
                 createUser·p0.999:  12.432 ms/op
                 createUser·p0.9999: 20.218 ms/op
                 createUser·p1.00:   22.315 ms/op

Iteration   2: 4.051 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   0.817 ms/op
                 createUser·p0.50:   3.899 ms/op
                 createUser·p0.90:   5.079 ms/op
                 createUser·p0.95:   5.546 ms/op
                 createUser·p0.99:   7.944 ms/op
                 createUser·p0.999:  12.815 ms/op
                 createUser·p0.9999: 21.237 ms/op
                 createUser·p1.00:   22.217 ms/op

Iteration   3: 3.883 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.124 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.841 ms/op
                 createUser·p0.95:   5.235 ms/op
                 createUser·p0.99:   6.455 ms/op
                 createUser·p0.999:  12.592 ms/op
                 createUser·p0.9999: 21.112 ms/op
                 createUser·p1.00:   23.265 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 245518
  mean =      3.909 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4555 
    [ 2.500,  5.000) = 220927 
    [ 5.000,  7.500) = 18308 
    [ 7.500, 10.000) = 1237 
    [10.000, 12.500) = 238 
    [12.500, 15.000) = 69 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 88 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.817 ms/op
     p(50.0000) =      3.789 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.300 ms/op
     p(99.0000) =      6.922 ms/op
     p(99.9000) =     12.599 ms/op
     p(99.9900) =     21.150 ms/op
     p(99.9990) =     23.045 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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
# Warmup Iteration   1: 5.448 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 3.886 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.686 ±(99.9%) 0.009 ms/op
Iteration   1: 3.688 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.025 ms/op
                 existUser·p0.50:   3.584 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   4.940 ms/op
                 existUser·p0.99:   6.038 ms/op
                 existUser·p0.999:  10.761 ms/op
                 existUser·p0.9999: 14.352 ms/op
                 existUser·p1.00:   20.939 ms/op

Iteration   2: 3.670 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   0.963 ms/op
                 existUser·p0.50:   3.551 ms/op
                 existUser·p0.90:   4.440 ms/op
                 existUser·p0.95:   4.866 ms/op
                 existUser·p0.99:   6.863 ms/op
                 existUser·p0.999:  11.574 ms/op
                 existUser·p0.9999: 16.164 ms/op
                 existUser·p1.00:   16.499 ms/op

Iteration   3: 3.566 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.937 ms/op
                 existUser·p0.50:   3.514 ms/op
                 existUser·p0.90:   4.268 ms/op
                 existUser·p0.95:   4.596 ms/op
                 existUser·p0.99:   5.718 ms/op
                 existUser·p0.999:  10.338 ms/op
                 existUser·p0.9999: 16.729 ms/op
                 existUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 263638
  mean =      3.641 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5494 
    [ 2.500,  5.000) = 248511 
    [ 5.000,  7.500) = 8303 
    [ 7.500, 10.000) = 956 
    [10.000, 12.500) = 212 
    [12.500, 15.000) = 57 
    [15.000, 17.500) = 103 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.937 ms/op
     p(50.0000) =      3.547 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.817 ms/op
     p(99.0000) =      6.242 ms/op
     p(99.9000) =     10.699 ms/op
     p(99.9900) =     16.427 ms/op
     p(99.9990) =     17.507 ms/op
     p(99.9999) =     20.939 ms/op
    p(100.0000) =     20.939 ms/op


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
# Warmup Iteration   1: 5.468 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.156 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.924 ±(99.9%) 0.010 ms/op
Iteration   1: 3.950 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.202 ms/op
                 getUser·p0.50:   3.858 ms/op
                 getUser·p0.90:   4.882 ms/op
                 getUser·p0.95:   5.243 ms/op
                 getUser·p0.99:   6.816 ms/op
                 getUser·p0.999:  13.371 ms/op
                 getUser·p0.9999: 16.872 ms/op
                 getUser·p1.00:   17.170 ms/op

Iteration   2: 3.880 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.041 ms/op
                 getUser·p0.50:   3.793 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.071 ms/op
                 getUser·p0.99:   6.234 ms/op
                 getUser·p0.999:  10.256 ms/op
                 getUser·p0.9999: 16.749 ms/op
                 getUser·p1.00:   17.039 ms/op

Iteration   3: 3.957 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   0.841 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.899 ms/op
                 getUser·p0.95:   5.251 ms/op
                 getUser·p0.99:   6.857 ms/op
                 getUser·p0.999:  11.226 ms/op
                 getUser·p0.9999: 18.047 ms/op
                 getUser·p1.00:   18.416 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 244190
  mean =      3.929 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 25 
    [ 1.250,  2.500) = 3364 
    [ 2.500,  3.750) = 107384 
    [ 3.750,  5.000) = 115677 
    [ 5.000,  6.250) = 14552 
    [ 6.250,  7.500) = 1689 
    [ 7.500,  8.750) = 731 
    [ 8.750, 10.000) = 305 
    [10.000, 11.250) = 198 
    [11.250, 12.500) = 75 
    [12.500, 13.750) = 58 
    [13.750, 15.000) = 39 
    [15.000, 16.250) = 32 
    [16.250, 17.500) = 45 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.841 ms/op
     p(50.0000) =      3.830 ms/op
     p(90.0000) =      4.841 ms/op
     p(95.0000) =      5.194 ms/op
     p(99.0000) =      6.660 ms/op
     p(99.9000) =     11.502 ms/op
     p(99.9900) =     16.960 ms/op
     p(99.9990) =     18.288 ms/op
     p(99.9999) =     18.416 ms/op
    p(100.0000) =     18.416 ms/op


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
# Warmup Iteration   1: 7.252 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.239 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.110 ±(99.9%) 0.018 ms/op
Iteration   1: 5.043 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.124 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   6.472 ms/op
                 listUser·p0.95:   7.324 ms/op
                 listUser·p0.99:   9.748 ms/op
                 listUser·p0.999:  19.661 ms/op
                 listUser·p0.9999: 23.809 ms/op
                 listUser·p1.00:   24.216 ms/op

Iteration   2: 5.073 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.434 ms/op
                 listUser·p0.50:   4.841 ms/op
                 listUser·p0.90:   6.447 ms/op
                 listUser·p0.95:   7.283 ms/op
                 listUser·p0.99:   9.282 ms/op
                 listUser·p0.999:  21.167 ms/op
                 listUser·p0.9999: 24.402 ms/op
                 listUser·p1.00:   25.264 ms/op

Iteration   3: 5.061 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.339 ms/op
                 listUser·p0.50:   4.825 ms/op
                 listUser·p0.90:   6.488 ms/op
                 listUser·p0.95:   7.389 ms/op
                 listUser·p0.99:   9.601 ms/op
                 listUser·p0.999:  18.535 ms/op
                 listUser·p0.9999: 21.301 ms/op
                 listUser·p1.00:   24.216 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 189717
  mean =      5.059 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203 
    [ 2.500,  5.000) = 111138 
    [ 5.000,  7.500) = 70076 
    [ 7.500, 10.000) = 6793 
    [10.000, 12.500) = 925 
    [12.500, 15.000) = 227 
    [15.000, 17.500) = 67 
    [17.500, 20.000) = 109 
    [20.000, 22.500) = 126 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      4.825 ms/op
     p(90.0000) =      6.472 ms/op
     p(95.0000) =      7.332 ms/op
     p(99.0000) =      9.552 ms/op
     p(99.9000) =     19.778 ms/op
     p(99.9900) =     24.085 ms/op
     p(99.9990) =     24.911 ms/op
     p(99.9999) =     25.264 ms/op
    p(100.0000) =     25.264 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.114 ± 2.232  ops/ms
ClientGrpc.existUser                       thrpt       3   8.695 ± 2.210  ops/ms
ClientGrpc.getUser                         thrpt       3   8.245 ± 1.942  ops/ms
ClientGrpc.listUser                        thrpt       3   5.961 ± 5.554  ops/ms
ClientGrpc.createUser                       avgt       3   4.091 ± 0.985   ms/op
ClientGrpc.existUser                        avgt       3   3.593 ± 1.287   ms/op
ClientGrpc.getUser                          avgt       3   3.979 ± 1.194   ms/op
ClientGrpc.listUser                         avgt       3   4.966 ± 0.766   ms/op
ClientGrpc.createUser                     sample  245518   3.909 ± 0.006   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.817           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.789           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.874           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           5.300           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           6.922           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          12.599           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          21.150           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          23.265           ms/op
ClientGrpc.existUser                      sample  263638   3.641 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.937           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.547           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.440           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.817           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           6.242           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          10.699           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          16.427           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.939           ms/op
ClientGrpc.getUser                        sample  244190   3.929 ± 0.006   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.841           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.830           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.841           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           5.194           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.660           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.502           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          16.960           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          18.416           ms/op
ClientGrpc.listUser                       sample  189717   5.059 ± 0.010   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           1.124           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.825           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.472           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           7.332           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           9.552           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          19.778           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.085           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          25.264           ms/op
