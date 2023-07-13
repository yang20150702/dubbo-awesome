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
# Warmup Iteration   1: 3.258 ops/ms
# Warmup Iteration   2: 7.108 ops/ms
# Warmup Iteration   3: 8.250 ops/ms
Iteration   1: 8.555 ops/ms
Iteration   2: 8.661 ops/ms
Iteration   3: 8.574 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  8.597 ±(99.9%) 1.027 ops/ms [Average]
  (min, avg, max) = (8.555, 8.597, 8.661), stdev = 0.056
  CI (99.9%): [7.569, 9.624] (assumes normal distribution)


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
# Warmup Iteration   1: 6.161 ops/ms
# Warmup Iteration   2: 8.717 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 9.435 ops/ms
Iteration   2: 9.297 ops/ms
Iteration   3: 9.333 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  9.355 ±(99.9%) 1.310 ops/ms [Average]
  (min, avg, max) = (9.297, 9.355, 9.435), stdev = 0.072
  CI (99.9%): [8.045, 10.664] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:55
# Fork: 1 of 1
# Warmup Iteration   1: 5.595 ops/ms
# Warmup Iteration   2: 8.226 ops/ms
# Warmup Iteration   3: 8.478 ops/ms
Iteration   1: 8.789 ops/ms
Iteration   2: 8.787 ops/ms
Iteration   3: 8.635 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  8.737 ±(99.9%) 1.608 ops/ms [Average]
  (min, avg, max) = (8.635, 8.737, 8.789), stdev = 0.088
  CI (99.9%): [7.129, 10.345] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:49
# Fork: 1 of 1
# Warmup Iteration   1: 4.272 ops/ms
# Warmup Iteration   2: 6.342 ops/ms
# Warmup Iteration   3: 6.706 ops/ms
Iteration   1: 6.629 ops/ms
Iteration   2: 6.603 ops/ms
Iteration   3: 6.721 ops/ms


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  6.651 ±(99.9%) 1.134 ops/ms [Average]
  (min, avg, max) = (6.603, 6.651, 6.721), stdev = 0.062
  CI (99.9%): [5.517, 7.785] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 5.501 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.782 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.752 ±(99.9%) 0.004 ms/op
Iteration   1: 3.547 ±(99.9%) 0.003 ms/op
Iteration   2: 3.530 ±(99.9%) 0.003 ms/op
Iteration   3: 3.621 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  3.566 ±(99.9%) 0.882 ms/op [Average]
  (min, avg, max) = (3.530, 3.566, 3.621), stdev = 0.048
  CI (99.9%): [2.684, 4.448] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 4.832 ±(99.9%) 0.017 ms/op
# Warmup Iteration   2: 3.531 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.566 ±(99.9%) 0.003 ms/op
Iteration   1: 3.527 ±(99.9%) 0.002 ms/op
Iteration   2: 3.395 ±(99.9%) 0.003 ms/op
Iteration   3: 3.488 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  3.470 ±(99.9%) 1.236 ms/op [Average]
  (min, avg, max) = (3.395, 3.470, 3.527), stdev = 0.068
  CI (99.9%): [2.234, 4.706] (assumes normal distribution)


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
# Warmup Iteration   1: 5.223 ±(99.9%) 0.016 ms/op
# Warmup Iteration   2: 3.819 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.614 ±(99.9%) 0.004 ms/op
Iteration   1: 3.598 ±(99.9%) 0.003 ms/op
Iteration   2: 3.670 ±(99.9%) 0.005 ms/op
Iteration   3: 3.616 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  3.628 ±(99.9%) 0.685 ms/op [Average]
  (min, avg, max) = (3.598, 3.628, 3.670), stdev = 0.038
  CI (99.9%): [2.943, 4.312] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 6.515 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 5.091 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.765 ±(99.9%) 0.018 ms/op
Iteration   1: 4.789 ±(99.9%) 0.020 ms/op
Iteration   2: 4.714 ±(99.9%) 0.021 ms/op
Iteration   3: 4.779 ±(99.9%) 0.022 ms/op


Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  4.760 ±(99.9%) 0.742 ms/op [Average]
  (min, avg, max) = (4.714, 4.760, 4.789), stdev = 0.041
  CI (99.9%): [4.018, 5.503] (assumes normal distribution)


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
# Warmup Iteration   1: 5.605 ±(99.9%) 0.057 ms/op
# Warmup Iteration   2: 3.905 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.747 ±(99.9%) 0.012 ms/op
Iteration   1: 3.618 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.884 ms/op
                 createUser·p0.50:   3.559 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.653 ms/op
                 createUser·p0.99:   5.972 ms/op
                 createUser·p0.999:  9.053 ms/op
                 createUser·p0.9999: 19.071 ms/op
                 createUser·p1.00:   19.235 ms/op

Iteration   2: 3.624 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.640 ms/op
                 createUser·p0.50:   3.555 ms/op
                 createUser·p0.90:   4.309 ms/op
                 createUser·p0.95:   4.669 ms/op
                 createUser·p0.99:   5.915 ms/op
                 createUser·p0.999:  11.080 ms/op
                 createUser·p0.9999: 20.584 ms/op
                 createUser·p1.00:   20.972 ms/op

Iteration   3: 3.579 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.770 ms/op
                 createUser·p0.50:   3.510 ms/op
                 createUser·p0.90:   4.121 ms/op
                 createUser·p0.95:   4.456 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  13.910 ms/op
                 createUser·p0.9999: 29.532 ms/op
                 createUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.createUser":
  N = 266053
  mean =      3.606 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7964 
    [ 2.500,  5.000) = 250827 
    [ 5.000,  7.500) = 6366 
    [ 7.500, 10.000) = 614 
    [10.000, 12.500) = 50 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 32 
    [17.500, 20.000) = 56 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 10 
    [27.500, 30.000) = 21 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.640 ms/op
     p(50.0000) =      3.543 ms/op
     p(90.0000) =      4.235 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     10.337 ms/op
     p(99.9900) =     27.374 ms/op
     p(99.9990) =     29.874 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 4.693 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.759 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.008 ms/op
Iteration   1: 3.442 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.874 ms/op
                 existUser·p0.50:   3.387 ms/op
                 existUser·p0.90:   3.928 ms/op
                 existUser·p0.95:   4.276 ms/op
                 existUser·p0.99:   5.521 ms/op
                 existUser·p0.999:  8.389 ms/op
                 existUser·p0.9999: 20.829 ms/op
                 existUser·p1.00:   21.758 ms/op

Iteration   2: 3.496 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.767 ms/op
                 existUser·p0.50:   3.424 ms/op
                 existUser·p0.90:   4.194 ms/op
                 existUser·p0.95:   4.538 ms/op
                 existUser·p0.99:   5.874 ms/op
                 existUser·p0.999:  10.412 ms/op
                 existUser·p0.9999: 16.756 ms/op
                 existUser·p1.00:   17.236 ms/op

Iteration   3: 3.543 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.909 ms/op
                 existUser·p0.50:   3.453 ms/op
                 existUser·p0.90:   4.174 ms/op
                 existUser·p0.95:   4.440 ms/op
                 existUser·p0.99:   5.685 ms/op
                 existUser·p0.999:  16.997 ms/op
                 existUser·p0.9999: 23.690 ms/op
                 existUser·p1.00:   26.214 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.existUser":
  N = 274829
  mean =      3.493 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6846 
    [ 2.500,  5.000) = 262510 
    [ 5.000,  7.500) = 4596 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 100 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 55 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 3 

  Percentiles, ms/op:
      p(0.0000) =      0.767 ms/op
     p(50.0000) =      3.420 ms/op
     p(90.0000) =      4.116 ms/op
     p(95.0000) =      4.424 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     11.275 ms/op
     p(99.9900) =     23.151 ms/op
     p(99.9990) =     25.789 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


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
# Warmup Iteration   1: 5.024 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 3.957 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.010 ms/op
Iteration   1: 3.660 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.717 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.284 ms/op
                 getUser·p0.95:   4.686 ms/op
                 getUser·p0.99:   6.144 ms/op
                 getUser·p0.999:  10.830 ms/op
                 getUser·p0.9999: 15.741 ms/op
                 getUser·p1.00:   16.089 ms/op

Iteration   2: 3.658 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.900 ms/op
                 getUser·p0.50:   3.596 ms/op
                 getUser·p0.90:   4.366 ms/op
                 getUser·p0.95:   4.702 ms/op
                 getUser·p0.99:   6.103 ms/op
                 getUser·p0.999:  11.740 ms/op
                 getUser·p0.9999: 16.425 ms/op
                 getUser·p1.00:   18.350 ms/op

Iteration   3: 3.620 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.759 ms/op
                 getUser·p0.50:   3.559 ms/op
                 getUser·p0.90:   4.276 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   5.915 ms/op
                 getUser·p0.999:  9.759 ms/op
                 getUser·p0.9999: 18.421 ms/op
                 getUser·p1.00:   20.677 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.getUser":
  N = 263405
  mean =      3.646 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8001 
    [ 2.500,  5.000) = 247501 
    [ 5.000,  7.500) = 6837 
    [ 7.500, 10.000) = 767 
    [10.000, 12.500) = 146 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 76 
    [17.500, 20.000) = 27 
    [20.000, 22.500) = 4 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.717 ms/op
     p(50.0000) =      3.584 ms/op
     p(90.0000) =      4.317 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     11.043 ms/op
     p(99.9900) =     17.880 ms/op
     p(99.9990) =     20.570 ms/op
     p(99.9999) =     20.677 ms/op
    p(100.0000) =     20.677 ms/op


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
# Warmup Iteration   1: 5.974 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.121 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.794 ±(99.9%) 0.014 ms/op
Iteration   1: 4.759 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.043 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.997 ms/op
                 listUser·p0.95:   6.881 ms/op
                 listUser·p0.99:   8.684 ms/op
                 listUser·p0.999:  14.247 ms/op
                 listUser·p0.9999: 16.453 ms/op
                 listUser·p1.00:   19.268 ms/op

Iteration   2: 4.750 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.583 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   6.755 ms/op
                 listUser·p0.99:   8.191 ms/op
                 listUser·p0.999:  16.187 ms/op
                 listUser·p0.9999: 19.325 ms/op
                 listUser·p1.00:   20.906 ms/op

Iteration   3: 4.878 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.928 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.037 ms/op
                 listUser·p0.99:   9.011 ms/op
                 listUser·p0.999:  20.328 ms/op
                 listUser·p0.9999: 27.187 ms/op
                 listUser·p1.00:   28.443 ms/op



Result "org.apache.dubbo.benchmark.ClientGrpc.listUser":
  N = 200163
  mean =      4.795 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 389 
    [ 2.500,  5.000) = 146582 
    [ 5.000,  7.500) = 47451 
    [ 7.500, 10.000) = 4874 
    [10.000, 12.500) = 498 
    [12.500, 15.000) = 139 
    [15.000, 17.500) = 111 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 34 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 27 

  Percentiles, ms/op:
      p(0.0000) =      0.928 ms/op
     p(50.0000) =      4.588 ms/op
     p(90.0000) =      6.013 ms/op
     p(95.0000) =      6.889 ms/op
     p(99.0000) =      8.618 ms/op
     p(99.9000) =     15.824 ms/op
     p(99.9900) =     26.770 ms/op
     p(99.9990) =     28.344 ms/op
     p(99.9999) =     28.443 ms/op
    p(100.0000) =     28.443 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                   Mode     Cnt   Score   Error   Units
ClientGrpc.createUser                      thrpt       3   8.597 ± 1.027  ops/ms
ClientGrpc.existUser                       thrpt       3   9.355 ± 1.310  ops/ms
ClientGrpc.getUser                         thrpt       3   8.737 ± 1.608  ops/ms
ClientGrpc.listUser                        thrpt       3   6.651 ± 1.134  ops/ms
ClientGrpc.createUser                       avgt       3   3.566 ± 0.882   ms/op
ClientGrpc.existUser                        avgt       3   3.470 ± 1.236   ms/op
ClientGrpc.getUser                          avgt       3   3.628 ± 0.685   ms/op
ClientGrpc.listUser                         avgt       3   4.760 ± 0.742   ms/op
ClientGrpc.createUser                     sample  266053   3.606 ± 0.005   ms/op
ClientGrpc.createUser:createUser·p0.00    sample           0.640           ms/op
ClientGrpc.createUser:createUser·p0.50    sample           3.543           ms/op
ClientGrpc.createUser:createUser·p0.90    sample           4.235           ms/op
ClientGrpc.createUser:createUser·p0.95    sample           4.604           ms/op
ClientGrpc.createUser:createUser·p0.99    sample           5.898           ms/op
ClientGrpc.createUser:createUser·p0.999   sample          10.337           ms/op
ClientGrpc.createUser:createUser·p0.9999  sample          27.374           ms/op
ClientGrpc.createUser:createUser·p1.00    sample          30.015           ms/op
ClientGrpc.existUser                      sample  274829   3.493 ± 0.005   ms/op
ClientGrpc.existUser:existUser·p0.00      sample           0.767           ms/op
ClientGrpc.existUser:existUser·p0.50      sample           3.420           ms/op
ClientGrpc.existUser:existUser·p0.90      sample           4.116           ms/op
ClientGrpc.existUser:existUser·p0.95      sample           4.424           ms/op
ClientGrpc.existUser:existUser·p0.99      sample           5.669           ms/op
ClientGrpc.existUser:existUser·p0.999     sample          11.275           ms/op
ClientGrpc.existUser:existUser·p0.9999    sample          23.151           ms/op
ClientGrpc.existUser:existUser·p1.00      sample          26.214           ms/op
ClientGrpc.getUser                        sample  263405   3.646 ± 0.005   ms/op
ClientGrpc.getUser:getUser·p0.00          sample           0.717           ms/op
ClientGrpc.getUser:getUser·p0.50          sample           3.584           ms/op
ClientGrpc.getUser:getUser·p0.90          sample           4.317           ms/op
ClientGrpc.getUser:getUser·p0.95          sample           4.686           ms/op
ClientGrpc.getUser:getUser·p0.99          sample           6.038           ms/op
ClientGrpc.getUser:getUser·p0.999         sample          11.043           ms/op
ClientGrpc.getUser:getUser·p0.9999        sample          17.880           ms/op
ClientGrpc.getUser:getUser·p1.00          sample          20.677           ms/op
ClientGrpc.listUser                       sample  200163   4.795 ± 0.009   ms/op
ClientGrpc.listUser:listUser·p0.00        sample           0.928           ms/op
ClientGrpc.listUser:listUser·p0.50        sample           4.588           ms/op
ClientGrpc.listUser:listUser·p0.90        sample           6.013           ms/op
ClientGrpc.listUser:listUser·p0.95        sample           6.889           ms/op
ClientGrpc.listUser:listUser·p0.99        sample           8.618           ms/op
ClientGrpc.listUser:listUser·p0.999       sample          15.824           ms/op
ClientGrpc.listUser:listUser·p0.9999      sample          26.770           ms/op
ClientGrpc.listUser:listUser·p1.00        sample          28.443           ms/op
