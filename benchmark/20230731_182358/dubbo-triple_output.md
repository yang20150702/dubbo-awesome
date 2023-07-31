# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.913 ops/ms
# Warmup Iteration   2: 4.887 ops/ms
# Warmup Iteration   3: 8.721 ops/ms
Iteration   1: 8.707 ops/ms
Iteration   2: 9.027 ops/ms
Iteration   3: 9.347 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.027 ±(99.9%) 5.836 ops/ms [Average]
  (min, avg, max) = (8.707, 9.027, 9.347), stdev = 0.320
  CI (99.9%): [3.191, 14.862] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 2.919 ops/ms
# Warmup Iteration   2: 8.779 ops/ms
# Warmup Iteration   3: 9.017 ops/ms
Iteration   1: 9.266 ops/ms
Iteration   2: 9.753 ops/ms
Iteration   3: 9.598 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.539 ±(99.9%) 4.536 ops/ms [Average]
  (min, avg, max) = (9.266, 9.539, 9.753), stdev = 0.249
  CI (99.9%): [5.003, 14.075] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.688 ops/ms
# Warmup Iteration   2: 7.927 ops/ms
# Warmup Iteration   3: 8.951 ops/ms
Iteration   1: 8.905 ops/ms
Iteration   2: 9.134 ops/ms
Iteration   3: 9.330 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.123 ±(99.9%) 3.887 ops/ms [Average]
  (min, avg, max) = (8.905, 9.123, 9.330), stdev = 0.213
  CI (99.9%): [5.236, 13.010] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.736 ops/ms
# Warmup Iteration   2: 7.266 ops/ms
# Warmup Iteration   3: 7.672 ops/ms
Iteration   1: 7.858 ops/ms
Iteration   2: 7.881 ops/ms
Iteration   3: 8.006 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.915 ±(99.9%) 1.451 ops/ms [Average]
  (min, avg, max) = (7.858, 7.915, 8.006), stdev = 0.080
  CI (99.9%): [6.464, 9.366] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 10.785 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.060 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.618 ±(99.9%) 0.006 ms/op
Iteration   1: 3.450 ±(99.9%) 0.009 ms/op
Iteration   2: 3.546 ±(99.9%) 0.005 ms/op
Iteration   3: 3.435 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.477 ±(99.9%) 1.099 ms/op [Average]
  (min, avg, max) = (3.435, 3.477, 3.546), stdev = 0.060
  CI (99.9%): [2.378, 4.576] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.453 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.611 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.375 ±(99.9%) 0.006 ms/op
Iteration   1: 3.272 ±(99.9%) 0.011 ms/op
Iteration   2: 3.316 ±(99.9%) 0.010 ms/op
Iteration   3: 3.359 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.316 ±(99.9%) 0.789 ms/op [Average]
  (min, avg, max) = (3.272, 3.316, 3.359), stdev = 0.043
  CI (99.9%): [2.526, 4.105] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 10.843 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.807 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.513 ±(99.9%) 0.002 ms/op
Iteration   1: 3.446 ±(99.9%) 0.007 ms/op
Iteration   2: 3.374 ±(99.9%) 0.008 ms/op
Iteration   3: 3.361 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.394 ±(99.9%) 0.835 ms/op [Average]
  (min, avg, max) = (3.361, 3.394, 3.446), stdev = 0.046
  CI (99.9%): [2.558, 4.229] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.617 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.586 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.147 ±(99.9%) 0.011 ms/op
Iteration   1: 4.069 ±(99.9%) 0.009 ms/op
Iteration   2: 4.095 ±(99.9%) 0.009 ms/op
Iteration   3: 4.012 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.059 ±(99.9%) 0.771 ms/op [Average]
  (min, avg, max) = (4.012, 4.059, 4.095), stdev = 0.042
  CI (99.9%): [3.287, 4.830] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 9.683 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.053 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.502 ±(99.9%) 0.012 ms/op
Iteration   1: 3.382 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.458 ms/op
                 createUser·p0.50:   3.236 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.084 ms/op
                 createUser·p0.99:   5.759 ms/op
                 createUser·p0.999:  20.691 ms/op
                 createUser·p0.9999: 24.141 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.456 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   3.969 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.627 ms/op
                 createUser·p0.999:  22.505 ms/op
                 createUser·p0.9999: 24.929 ms/op
                 createUser·p1.00:   25.788 ms/op

Iteration   3: 3.496 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.737 ms/op
                 createUser·p0.50:   3.391 ms/op
                 createUser·p0.90:   3.953 ms/op
                 createUser·p0.95:   4.375 ms/op
                 createUser·p0.99:   6.475 ms/op
                 createUser·p0.999:  16.426 ms/op
                 createUser·p0.9999: 30.207 ms/op
                 createUser·p1.00:   30.966 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277215
  mean =      3.461 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4198 
    [ 2.500,  5.000) = 265844 
    [ 5.000,  7.500) = 5991 
    [ 7.500, 10.000) = 574 
    [10.000, 12.500) = 171 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 25 
    [20.000, 22.500) = 84 
    [22.500, 25.000) = 141 
    [25.000, 27.500) = 12 
    [27.500, 30.000) = 19 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.456 ms/op
     p(50.0000) =      3.310 ms/op
     p(90.0000) =      3.913 ms/op
     p(95.0000) =      4.268 ms/op
     p(99.0000) =      6.349 ms/op
     p(99.9000) =     18.766 ms/op
     p(99.9900) =     28.324 ms/op
     p(99.9990) =     30.835 ms/op
     p(99.9999) =     30.966 ms/op
    p(100.0000) =     30.966 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.710 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 3.615 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.009 ms/op
Iteration   1: 3.432 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.350 ms/op
                 existUser·p0.50:   3.285 ms/op
                 existUser·p0.90:   3.764 ms/op
                 existUser·p0.95:   4.334 ms/op
                 existUser·p0.99:   6.693 ms/op
                 existUser·p0.999:  20.332 ms/op
                 existUser·p0.9999: 22.970 ms/op
                 existUser·p1.00:   23.855 ms/op

Iteration   2: 3.415 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.548 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.899 ms/op
                 existUser·p0.95:   4.190 ms/op
                 existUser·p0.99:   5.841 ms/op
                 existUser·p0.999:  9.470 ms/op
                 existUser·p0.9999: 24.137 ms/op
                 existUser·p1.00:   24.773 ms/op

Iteration   3: 3.513 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   0.434 ms/op
                 existUser·p0.50:   3.359 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.735 ms/op
                 existUser·p0.99:   7.066 ms/op
                 existUser·p0.999:  26.034 ms/op
                 existUser·p0.9999: 29.688 ms/op
                 existUser·p1.00:   30.867 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 277626
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4705 
    [ 2.500,  5.000) = 266019 
    [ 5.000,  7.500) = 5723 
    [ 7.500, 10.000) = 813 
    [10.000, 12.500) = 94 
    [12.500, 15.000) = 10 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 1 
    [20.000, 22.500) = 90 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 43 
    [30.000, 32.500) = 7 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.434 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.440 ms/op
     p(99.0000) =      6.496 ms/op
     p(99.9000) =     11.911 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     30.776 ms/op
     p(99.9999) =     30.867 ms/op
    p(100.0000) =     30.867 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.456 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.789 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.629 ±(99.9%) 0.012 ms/op
Iteration   1: 3.495 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.561 ms/op
                 getUser·p0.50:   3.334 ms/op
                 getUser·p0.90:   3.879 ms/op
                 getUser·p0.95:   4.260 ms/op
                 getUser·p0.99:   6.742 ms/op
                 getUser·p0.999:  21.791 ms/op
                 getUser·p0.9999: 25.494 ms/op
                 getUser·p1.00:   25.625 ms/op

Iteration   2: 3.399 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.567 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.715 ms/op
                 getUser·p0.95:   3.912 ms/op
                 getUser·p0.99:   5.056 ms/op
                 getUser·p0.999:  21.818 ms/op
                 getUser·p0.9999: 24.805 ms/op
                 getUser·p1.00:   25.494 ms/op

Iteration   3: 3.486 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.362 ms/op
                 getUser·p0.50:   3.367 ms/op
                 getUser·p0.90:   3.822 ms/op
                 getUser·p0.95:   4.014 ms/op
                 getUser·p0.99:   6.070 ms/op
                 getUser·p0.999:  19.137 ms/op
                 getUser·p0.9999: 26.498 ms/op
                 getUser·p1.00:   27.427 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277534
  mean =      3.459 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 2998 
    [ 2.500,  5.000) = 268732 
    [ 5.000,  7.500) = 4719 
    [ 7.500, 10.000) = 505 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 19 
    [17.500, 20.000) = 33 
    [20.000, 22.500) = 99 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.362 ms/op
     p(50.0000) =      3.338 ms/op
     p(90.0000) =      3.805 ms/op
     p(95.0000) =      4.039 ms/op
     p(99.0000) =      6.078 ms/op
     p(99.9000) =     21.194 ms/op
     p(99.9900) =     25.625 ms/op
     p(99.9990) =     27.063 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_382, OpenJDK 64-Bit Server VM, 25.382-b05
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.382-5/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 11.877 ±(99.9%) 0.157 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.172 ±(99.9%) 0.014 ms/op
Iteration   1: 4.136 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.091 ms/op
                 listUser·p0.50:   3.920 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.732 ms/op
                 listUser·p0.999:  19.956 ms/op
                 listUser·p0.9999: 24.432 ms/op
                 listUser·p1.00:   26.313 ms/op

Iteration   2: 4.103 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.454 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.653 ms/op
                 listUser·p0.95:   4.940 ms/op
                 listUser·p0.99:   7.561 ms/op
                 listUser·p0.999:  15.876 ms/op
                 listUser·p0.9999: 22.518 ms/op
                 listUser·p1.00:   23.134 ms/op

Iteration   3: 4.018 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.940 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.637 ms/op
                 listUser·p0.99:   7.498 ms/op
                 listUser·p0.999:  15.319 ms/op
                 listUser·p0.9999: 19.171 ms/op
                 listUser·p1.00:   19.300 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 235003
  mean =      4.085 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 28 
    [ 2.500,  5.000) = 225054 
    [ 5.000,  7.500) = 7381 
    [ 7.500, 10.000) = 1802 
    [10.000, 12.500) = 244 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 181 
    [17.500, 20.000) = 65 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 48 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      2.091 ms/op
     p(50.0000) =      3.924 ms/op
     p(90.0000) =      4.563 ms/op
     p(95.0000) =      4.874 ms/op
     p(99.0000) =      7.635 ms/op
     p(99.9000) =     15.942 ms/op
     p(99.9900) =     23.577 ms/op
     p(99.9990) =     25.413 ms/op
     p(99.9999) =     26.313 ms/op
    p(100.0000) =     26.313 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.027 ± 5.836  ops/ms
ClientPb.existUser                       thrpt       3   9.539 ± 4.536  ops/ms
ClientPb.getUser                         thrpt       3   9.123 ± 3.887  ops/ms
ClientPb.listUser                        thrpt       3   7.915 ± 1.451  ops/ms
ClientPb.createUser                       avgt       3   3.477 ± 1.099   ms/op
ClientPb.existUser                        avgt       3   3.316 ± 0.789   ms/op
ClientPb.getUser                          avgt       3   3.394 ± 0.835   ms/op
ClientPb.listUser                         avgt       3   4.059 ± 0.771   ms/op
ClientPb.createUser                     sample  277215   3.461 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.456           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.310           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.913           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.268           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.349           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.766           ms/op
ClientPb.createUser:createUser·p0.9999  sample          28.324           ms/op
ClientPb.createUser:createUser·p1.00    sample          30.966           ms/op
ClientPb.existUser                      sample  277626   3.453 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.434           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.314           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.875           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.440           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.496           ms/op
ClientPb.existUser:existUser·p0.999     sample          11.911           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.867           ms/op
ClientPb.getUser                        sample  277534   3.459 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.362           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.338           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.805           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.039           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.194           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.625           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.427           ms/op
ClientPb.listUser                       sample  235003   4.085 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.091           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.924           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.563           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.874           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.635           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.942           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.577           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.313           ms/op
