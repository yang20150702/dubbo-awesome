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
# Warmup Iteration   1: 4.361 ops/ms
# Warmup Iteration   2: 9.492 ops/ms
# Warmup Iteration   3: 10.176 ops/ms
Iteration   1: 10.504 ops/ms
Iteration   2: 10.625 ops/ms
Iteration   3: 10.377 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  10.502 ±(99.9%) 2.264 ops/ms [Average]
  (min, avg, max) = (10.377, 10.502, 10.625), stdev = 0.124
  CI (99.9%): [8.238, 12.766] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:56
# Fork: 1 of 1
# Warmup Iteration   1: 7.814 ops/ms
# Warmup Iteration   2: 10.543 ops/ms
# Warmup Iteration   3: 11.102 ops/ms
Iteration   1: 10.944 ops/ms
Iteration   2: 10.746 ops/ms
Iteration   3: 11.096 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  10.928 ±(99.9%) 3.204 ops/ms [Average]
  (min, avg, max) = (10.746, 10.928, 11.096), stdev = 0.176
  CI (99.9%): [7.725, 14.132] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:50
# Fork: 1 of 1
# Warmup Iteration   1: 7.055 ops/ms
# Warmup Iteration   2: 10.406 ops/ms
# Warmup Iteration   3: 10.691 ops/ms
Iteration   1: 10.664 ops/ms
Iteration   2: 10.673 ops/ms
Iteration   3: 10.771 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  10.702 ±(99.9%) 1.092 ops/ms [Average]
  (min, avg, max) = (10.664, 10.702, 10.771), stdev = 0.060
  CI (99.9%): [9.611, 11.794] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:46
# Fork: 1 of 1
# Warmup Iteration   1: 6.471 ops/ms
# Warmup Iteration   2: 8.110 ops/ms
# Warmup Iteration   3: 8.243 ops/ms
Iteration   1: 8.373 ops/ms
Iteration   2: 8.275 ops/ms
Iteration   3: 8.253 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  8.301 ±(99.9%) 1.164 ops/ms [Average]
  (min, avg, max) = (8.253, 8.301, 8.373), stdev = 0.064
  CI (99.9%): [7.137, 9.464] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:40
# Fork: 1 of 1
# Warmup Iteration   1: 3.761 ±(99.9%) 0.012 ms/op
# Warmup Iteration   2: 3.062 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 2.985 ±(99.9%) 0.005 ms/op
Iteration   1: 2.909 ±(99.9%) 0.003 ms/op
Iteration   2: 3.010 ±(99.9%) 0.002 ms/op
Iteration   3: 3.043 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  2.987 ±(99.9%) 1.277 ms/op [Average]
  (min, avg, max) = (2.909, 2.987, 3.043), stdev = 0.070
  CI (99.9%): [1.710, 4.265] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:35
# Fork: 1 of 1
# Warmup Iteration   1: 3.587 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 2.890 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 2.887 ±(99.9%) 0.005 ms/op
Iteration   1: 2.899 ±(99.9%) 0.003 ms/op
Iteration   2: 2.910 ±(99.9%) 0.002 ms/op
Iteration   3: 2.889 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  2.899 ±(99.9%) 0.186 ms/op [Average]
  (min, avg, max) = (2.889, 2.899, 2.910), stdev = 0.010
  CI (99.9%): [2.713, 3.086] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:30
# Fork: 1 of 1
# Warmup Iteration   1: 4.037 ±(99.9%) 0.010 ms/op
# Warmup Iteration   2: 3.083 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 3.032 ±(99.9%) 0.002 ms/op
Iteration   1: 3.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.009 ±(99.9%) 0.003 ms/op
Iteration   3: 2.955 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.006 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (2.955, 3.006, 3.056), stdev = 0.050
  CI (99.9%): [2.086, 3.927] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:25
# Fork: 1 of 1
# Warmup Iteration   1: 4.983 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.932 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.893 ±(99.9%) 0.009 ms/op
Iteration   1: 3.861 ±(99.9%) 0.011 ms/op
Iteration   2: 3.755 ±(99.9%) 0.034 ms/op
Iteration   3: 3.836 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  3.817 ±(99.9%) 1.008 ms/op [Average]
  (min, avg, max) = (3.755, 3.817, 3.861), stdev = 0.055
  CI (99.9%): [2.809, 4.825] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:20
# Fork: 1 of 1
# Warmup Iteration   1: 4.005 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.124 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.012 ±(99.9%) 0.007 ms/op
Iteration   1: 2.950 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.650 ms/op
                 createUser·p0.50:   2.966 ms/op
                 createUser·p0.90:   3.531 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.621 ms/op
                 createUser·p0.999:  6.472 ms/op
                 createUser·p0.9999: 11.507 ms/op
                 createUser·p1.00:   11.796 ms/op

Iteration   2: 3.057 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.887 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.613 ms/op
                 createUser·p0.95:   3.817 ms/op
                 createUser·p0.99:   4.645 ms/op
                 createUser·p0.999:  7.740 ms/op
                 createUser·p0.9999: 14.115 ms/op
                 createUser·p1.00:   14.385 ms/op

Iteration   3: 3.014 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   0.249 ms/op
                 createUser·p0.50:   3.023 ms/op
                 createUser·p0.90:   3.453 ms/op
                 createUser·p0.95:   3.727 ms/op
                 createUser·p0.99:   4.378 ms/op
                 createUser·p0.999:  8.776 ms/op
                 createUser·p0.9999: 15.303 ms/op
                 createUser·p1.00:   15.499 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 319153
  mean =      3.007 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 2829 
    [ 1.250,  2.500) = 25669 
    [ 2.500,  3.750) = 273327 
    [ 3.750,  5.000) = 15866 
    [ 5.000,  6.250) = 903 
    [ 6.250,  7.500) = 182 
    [ 7.500,  8.750) = 111 
    [ 8.750, 10.000) = 41 
    [10.000, 11.250) = 44 
    [11.250, 12.500) = 21 
    [12.500, 13.750) = 83 
    [13.750, 15.000) = 51 
    [15.000, 16.250) = 26 
    [16.250, 17.500) = 0 
    [17.500, 18.750) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.249 ms/op
     p(50.0000) =      3.006 ms/op
     p(90.0000) =      3.543 ms/op
     p(95.0000) =      3.777 ms/op
     p(99.0000) =      4.571 ms/op
     p(99.9000) =      7.938 ms/op
     p(99.9900) =     14.830 ms/op
     p(99.9990) =     15.401 ms/op
     p(99.9999) =     15.499 ms/op
    p(100.0000) =     15.499 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:15
# Fork: 1 of 1
# Warmup Iteration   1: 3.978 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.042 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 2.947 ±(99.9%) 0.006 ms/op
Iteration   1: 2.851 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.592 ms/op
                 existUser·p0.50:   2.855 ms/op
                 existUser·p0.90:   3.265 ms/op
                 existUser·p0.95:   3.535 ms/op
                 existUser·p0.99:   4.661 ms/op
                 existUser·p0.999:  7.534 ms/op
                 existUser·p0.9999: 19.719 ms/op
                 existUser·p1.00:   20.054 ms/op

Iteration   2: 2.897 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.497 ms/op
                 existUser·p0.50:   2.912 ms/op
                 existUser·p0.90:   3.383 ms/op
                 existUser·p0.95:   3.584 ms/op
                 existUser·p0.99:   4.309 ms/op
                 existUser·p0.999:  8.645 ms/op
                 existUser·p0.9999: 15.531 ms/op
                 existUser·p1.00:   16.024 ms/op

Iteration   3: 2.881 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.545 ms/op
                 existUser·p0.50:   2.896 ms/op
                 existUser·p0.90:   3.404 ms/op
                 existUser·p0.95:   3.621 ms/op
                 existUser·p0.99:   4.538 ms/op
                 existUser·p0.999:  10.437 ms/op
                 existUser·p0.9999: 17.593 ms/op
                 existUser·p1.00:   17.859 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 333525
  mean =      2.876 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 47088 
    [ 2.500,  5.000) = 284984 
    [ 5.000,  7.500) = 1025 
    [ 7.500, 10.000) = 173 
    [10.000, 12.500) = 95 
    [12.500, 15.000) = 31 
    [15.000, 17.500) = 83 
    [17.500, 20.000) = 45 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.497 ms/op
     p(50.0000) =      2.888 ms/op
     p(90.0000) =      3.359 ms/op
     p(95.0000) =      3.584 ms/op
     p(99.0000) =      4.555 ms/op
     p(99.9000) =      8.585 ms/op
     p(99.9900) =     17.859 ms/op
     p(99.9990) =     19.956 ms/op
     p(99.9999) =     20.054 ms/op
    p(100.0000) =     20.054 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 4.232 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 3.089 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.043 ±(99.9%) 0.006 ms/op
Iteration   1: 3.053 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.773 ms/op
                 getUser·p0.50:   3.031 ms/op
                 getUser·p0.90:   3.609 ms/op
                 getUser·p0.95:   3.789 ms/op
                 getUser·p0.99:   4.506 ms/op
                 getUser·p0.999:  7.045 ms/op
                 getUser·p0.9999: 17.646 ms/op
                 getUser·p1.00:   17.957 ms/op

Iteration   2: 3.078 ±(99.9%) 0.005 ms/op
                 getUser·p0.00:   0.701 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.564 ms/op
                 getUser·p0.95:   3.744 ms/op
                 getUser·p0.99:   4.407 ms/op
                 getUser·p0.999:  8.816 ms/op
                 getUser·p0.9999: 14.497 ms/op
                 getUser·p1.00:   14.746 ms/op

Iteration   3: 3.019 ±(99.9%) 0.006 ms/op
                 getUser·p0.00:   0.867 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.568 ms/op
                 getUser·p0.95:   3.764 ms/op
                 getUser·p0.99:   4.620 ms/op
                 getUser·p0.999:  6.341 ms/op
                 getUser·p0.9999: 17.203 ms/op
                 getUser·p1.00:   17.629 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 314618
  mean =      3.050 ±(99.9%) 0.003 ms/op

  Histogram, ms/op:
    [ 0.000,  1.250) = 838 
    [ 1.250,  2.500) = 21219 
    [ 2.500,  3.750) = 275792 
    [ 3.750,  5.000) = 15471 
    [ 5.000,  6.250) = 901 
    [ 6.250,  7.500) = 157 
    [ 7.500,  8.750) = 38 
    [ 8.750, 10.000) = 24 
    [10.000, 11.250) = 32 
    [11.250, 12.500) = 34 
    [12.500, 13.750) = 16 
    [13.750, 15.000) = 32 
    [15.000, 16.250) = 7 
    [16.250, 17.500) = 41 
    [17.500, 18.750) = 16 

  Percentiles, ms/op:
      p(0.0000) =      0.701 ms/op
     p(50.0000) =      3.031 ms/op
     p(90.0000) =      3.580 ms/op
     p(95.0000) =      3.768 ms/op
     p(99.0000) =      4.530 ms/op
     p(99.9000) =      6.806 ms/op
     p(99.9900) =     17.302 ms/op
     p(99.9990) =     17.887 ms/op
     p(99.9999) =     17.957 ms/op
    p(100.0000) =     17.957 ms/op


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
# Warmup Iteration   1: 4.828 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 3.943 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.879 ±(99.9%) 0.011 ms/op
Iteration   1: 3.925 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.169 ms/op
                 listUser·p0.50:   3.752 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.710 ms/op
                 listUser·p0.99:   7.021 ms/op
                 listUser·p0.999:  11.965 ms/op
                 listUser·p0.9999: 19.585 ms/op
                 listUser·p1.00:   19.923 ms/op

Iteration   2: 3.843 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   0.951 ms/op
                 listUser·p0.50:   3.674 ms/op
                 listUser·p0.90:   4.899 ms/op
                 listUser·p0.95:   5.448 ms/op
                 listUser·p0.99:   6.701 ms/op
                 listUser·p0.999:  15.899 ms/op
                 listUser·p0.9999: 22.152 ms/op
                 listUser·p1.00:   22.807 ms/op

Iteration   3: 3.784 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.051 ms/op
                 listUser·p0.50:   3.658 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   5.472 ms/op
                 listUser·p0.99:   6.586 ms/op
                 listUser·p0.999:  19.628 ms/op
                 listUser·p0.9999: 25.824 ms/op
                 listUser·p1.00:   26.247 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 249323
  mean =      3.850 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4817 
    [ 2.500,  5.000) = 222310 
    [ 5.000,  7.500) = 20992 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 128 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 103 
    [22.500, 25.000) = 13 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      0.951 ms/op
     p(50.0000) =      3.695 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.554 ms/op
     p(99.0000) =      6.783 ms/op
     p(99.9000) =     14.134 ms/op
     p(99.9900) =     24.906 ms/op
     p(99.9990) =     26.150 ms/op
     p(99.9999) =     26.247 ms/op
    p(100.0000) =     26.247 ms/op


# Run complete. Total time: 00:13:03

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3  10.502 ± 2.264  ops/ms
ClientGrpc.existUser                       thrpt       3  10.928 ± 3.204  ops/ms
ClientGrpc.getUser                         thrpt       3  10.702 ± 1.092  ops/ms
ClientGrpc.listUser                        thrpt       3   8.301 ± 1.164  ops/ms
ClientGrpc.createUser                       avgt       3   2.987 ± 1.277   ms/op
ClientGrpc.existUser                        avgt       3   2.899 ± 0.186   ms/op
ClientGrpc.getUser                          avgt       3   3.006 ± 0.921   ms/op
ClientGrpc.listUser                         avgt       3   3.817 ± 1.008   ms/op
ClientGrpc.createUser                     sample  319153   3.007 ± 0.004   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.249           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.006           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           3.777           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           4.571           ms/op
ClientGrpc.createUser:createUser·p0.999   sample           7.938           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          14.830           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          15.499           ms/op
ClientGrpc.existUser                      sample  333525   2.876 ± 0.004   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.497           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           2.888           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           3.359           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           3.584           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           4.555           ms/op
ClientGrpc.existUser:existUser·p0.999     sample           8.585           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          17.859           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          20.054           ms/op
ClientGrpc.getUser                        sample  314618   3.050 ± 0.003   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.701           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.031           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           3.580           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           3.768           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           4.530           ms/op
ClientGrpc.getUser:getUser·p0.999         sample           6.806           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.302           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          17.957           ms/op
ClientGrpc.listUser                       sample  249323   3.850 ± 0.007   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.951           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           3.695           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           4.891           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           5.554           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           6.783           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          14.134           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          24.906           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          26.247           ms/op
