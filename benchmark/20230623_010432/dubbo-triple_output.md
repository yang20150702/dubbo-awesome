# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.442 ops/ms
# Warmup Iteration   2: 3.310 ops/ms
# Warmup Iteration   3: 6.934 ops/ms
Iteration   1: 7.151 ops/ms
Iteration   2: 7.584 ops/ms
Iteration   3: 7.564 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.433 ±(99.9%) 4.461 ops/ms [Average]
  (min, avg, max) = (7.151, 7.433, 7.584), stdev = 0.245
  CI (99.9%): [2.972, 11.894] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.190 ops/ms
# Warmup Iteration   2: 6.474 ops/ms
# Warmup Iteration   3: 7.671 ops/ms
Iteration   1: 7.697 ops/ms
Iteration   2: 7.443 ops/ms
Iteration   3: 7.698 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.613 ±(99.9%) 2.684 ops/ms [Average]
  (min, avg, max) = (7.443, 7.613, 7.698), stdev = 0.147
  CI (99.9%): [4.929, 10.297] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.088 ops/ms
# Warmup Iteration   2: 6.001 ops/ms
# Warmup Iteration   3: 7.318 ops/ms
Iteration   1: 7.068 ops/ms
Iteration   2: 7.490 ops/ms
Iteration   3: 7.522 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.360 ±(99.9%) 4.617 ops/ms [Average]
  (min, avg, max) = (7.068, 7.360, 7.522), stdev = 0.253
  CI (99.9%): [2.743, 11.977] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 1.940 ops/ms
# Warmup Iteration   2: 5.036 ops/ms
# Warmup Iteration   3: 6.359 ops/ms
Iteration   1: 6.494 ops/ms
Iteration   2: 6.448 ops/ms
Iteration   3: 6.289 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.410 ±(99.9%) 1.965 ops/ms [Average]
  (min, avg, max) = (6.289, 6.410, 6.494), stdev = 0.108
  CI (99.9%): [4.446, 8.375] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 13.471 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 4.977 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.337 ±(99.9%) 0.006 ms/op
Iteration   1: 4.243 ±(99.9%) 0.006 ms/op
Iteration   2: 4.296 ±(99.9%) 0.008 ms/op
Iteration   3: 4.090 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.210 ±(99.9%) 1.957 ms/op [Average]
  (min, avg, max) = (4.090, 4.210, 4.296), stdev = 0.107
  CI (99.9%): [2.253, 6.167] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.590 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.730 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.073 ±(99.9%) 0.005 ms/op
Iteration   1: 4.086 ±(99.9%) 0.006 ms/op
Iteration   2: 4.059 ±(99.9%) 0.004 ms/op
Iteration   3: 4.022 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.056 ±(99.9%) 0.583 ms/op [Average]
  (min, avg, max) = (4.022, 4.056, 4.086), stdev = 0.032
  CI (99.9%): [3.472, 4.639] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.880 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 5.024 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.309 ±(99.9%) 0.006 ms/op
Iteration   1: 4.343 ±(99.9%) 0.009 ms/op
Iteration   2: 4.259 ±(99.9%) 0.007 ms/op
Iteration   3: 4.196 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.266 ±(99.9%) 1.342 ms/op [Average]
  (min, avg, max) = (4.196, 4.266, 4.343), stdev = 0.074
  CI (99.9%): [2.924, 5.608] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 14.154 ±(99.9%) 0.059 ms/op
# Warmup Iteration   2: 5.654 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.097 ±(99.9%) 0.006 ms/op
Iteration   1: 4.992 ±(99.9%) 0.013 ms/op
Iteration   2: 4.995 ±(99.9%) 0.014 ms/op
Iteration   3: 5.009 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.999 ±(99.9%) 0.165 ms/op [Average]
  (min, avg, max) = (4.992, 4.999, 5.009), stdev = 0.009
  CI (99.9%): [4.833, 5.164] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.543 ±(99.9%) 0.234 ms/op
# Warmup Iteration   2: 5.069 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.739 ±(99.9%) 0.022 ms/op
Iteration   1: 4.505 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   2.204 ms/op
                 createUser·p0.50:   4.174 ms/op
                 createUser·p0.90:   5.849 ms/op
                 createUser·p0.95:   6.816 ms/op
                 createUser·p0.99:   8.995 ms/op
                 createUser·p0.999:  25.789 ms/op
                 createUser·p0.9999: 29.422 ms/op
                 createUser·p1.00:   30.573 ms/op

Iteration   2: 4.376 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.483 ms/op
                 createUser·p0.50:   4.112 ms/op
                 createUser·p0.90:   5.472 ms/op
                 createUser·p0.95:   6.554 ms/op
                 createUser·p0.99:   8.913 ms/op
                 createUser·p0.999:  13.646 ms/op
                 createUser·p0.9999: 30.126 ms/op
                 createUser·p1.00:   31.949 ms/op

Iteration   3: 4.328 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   1.759 ms/op
                 createUser·p0.50:   4.080 ms/op
                 createUser·p0.90:   5.251 ms/op
                 createUser·p0.95:   6.218 ms/op
                 createUser·p0.99:   8.405 ms/op
                 createUser·p0.999:  20.677 ms/op
                 createUser·p0.9999: 34.264 ms/op
                 createUser·p1.00:   34.865 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 218007
  mean =      4.401 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 298 
    [ 2.500,  5.000) = 185501 
    [ 5.000,  7.500) = 27292 
    [ 7.500, 10.000) = 3836 
    [10.000, 12.500) = 693 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 23 
    [22.500, 25.000) = 8 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 86 
    [30.000, 32.500) = 26 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.483 ms/op
     p(50.0000) =      4.125 ms/op
     p(90.0000) =      5.530 ms/op
     p(95.0000) =      6.586 ms/op
     p(99.0000) =      8.831 ms/op
     p(99.9000) =     24.936 ms/op
     p(99.9900) =     33.161 ms/op
     p(99.9990) =     34.669 ms/op
     p(99.9999) =     34.865 ms/op
    p(100.0000) =     34.865 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.629 ±(99.9%) 0.178 ms/op
# Warmup Iteration   2: 4.548 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.266 ±(99.9%) 0.016 ms/op
Iteration   1: 4.083 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.497 ms/op
                 existUser·p0.50:   3.895 ms/op
                 existUser·p0.90:   4.768 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.930 ms/op
                 existUser·p0.999:  11.620 ms/op
                 existUser·p0.9999: 25.816 ms/op
                 existUser·p1.00:   26.739 ms/op

Iteration   2: 4.089 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.925 ms/op
                 existUser·p0.50:   3.916 ms/op
                 existUser·p0.90:   4.841 ms/op
                 existUser·p0.95:   5.800 ms/op
                 existUser·p0.99:   8.307 ms/op
                 existUser·p0.999:  12.776 ms/op
                 existUser·p0.9999: 28.538 ms/op
                 existUser·p1.00:   29.688 ms/op

Iteration   3: 4.235 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.980 ms/op
                 existUser·p0.50:   3.985 ms/op
                 existUser·p0.90:   5.153 ms/op
                 existUser·p0.95:   6.078 ms/op
                 existUser·p0.99:   8.200 ms/op
                 existUser·p0.999:  29.959 ms/op
                 existUser·p0.9999: 32.389 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 232083
  mean =      4.135 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 464 
    [ 2.500,  5.000) = 209904 
    [ 5.000,  7.500) = 18263 
    [ 7.500, 10.000) = 2716 
    [10.000, 12.500) = 355 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 29 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 35 
    [25.000, 27.500) = 62 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 69 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.497 ms/op
     p(50.0000) =      3.932 ms/op
     p(90.0000) =      4.932 ms/op
     p(95.0000) =      5.841 ms/op
     p(99.0000) =      8.159 ms/op
     p(99.9000) =     18.416 ms/op
     p(99.9900) =     31.883 ms/op
     p(99.9990) =     32.823 ms/op
     p(99.9999) =     34.210 ms/op
    p(100.0000) =     34.210 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 14.527 ±(99.9%) 0.187 ms/op
# Warmup Iteration   2: 4.772 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.500 ±(99.9%) 0.017 ms/op
Iteration   1: 4.207 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.884 ms/op
                 getUser·p0.50:   3.965 ms/op
                 getUser·p0.90:   5.030 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   8.438 ms/op
                 getUser·p0.999:  22.602 ms/op
                 getUser·p0.9999: 28.539 ms/op
                 getUser·p1.00:   30.573 ms/op

Iteration   2: 4.135 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   2.068 ms/op
                 getUser·p0.50:   4.006 ms/op
                 getUser·p0.90:   4.907 ms/op
                 getUser·p0.95:   5.456 ms/op
                 getUser·p0.99:   7.365 ms/op
                 getUser·p0.999:  10.431 ms/op
                 getUser·p0.9999: 25.657 ms/op
                 getUser·p1.00:   26.313 ms/op

Iteration   3: 4.132 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.403 ms/op
                 getUser·p0.50:   3.912 ms/op
                 getUser·p0.90:   4.809 ms/op
                 getUser·p0.95:   5.636 ms/op
                 getUser·p0.99:   8.069 ms/op
                 getUser·p0.999:  15.531 ms/op
                 getUser·p0.9999: 30.590 ms/op
                 getUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 230849
  mean =      4.157 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 273 
    [ 2.500,  5.000) = 209745 
    [ 5.000,  7.500) = 17660 
    [ 7.500, 10.000) = 2342 
    [10.000, 12.500) = 420 
    [12.500, 15.000) = 109 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 12 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 67 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 13 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.403 ms/op
     p(50.0000) =      3.965 ms/op
     p(90.0000) =      4.915 ms/op
     p(95.0000) =      5.677 ms/op
     p(99.0000) =      8.069 ms/op
     p(99.9000) =     21.271 ms/op
     p(99.9900) =     29.259 ms/op
     p(99.9990) =     30.928 ms/op
     p(99.9999) =     32.080 ms/op
    p(100.0000) =     32.080 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 14.379 ±(99.9%) 0.223 ms/op
# Warmup Iteration   2: 5.854 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.367 ±(99.9%) 0.024 ms/op
Iteration   1: 5.276 ±(99.9%) 0.022 ms/op
                 listUser·p0.00:   2.146 ms/op
                 listUser·p0.50:   4.899 ms/op
                 listUser·p0.90:   6.529 ms/op
                 listUser·p0.95:   7.922 ms/op
                 listUser·p0.99:   11.112 ms/op
                 listUser·p0.999:  26.083 ms/op
                 listUser·p0.9999: 35.320 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   2: 5.099 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.671 ms/op
                 listUser·p0.50:   4.776 ms/op
                 listUser·p0.90:   6.177 ms/op
                 listUser·p0.95:   7.345 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  24.510 ms/op
                 listUser·p0.9999: 29.703 ms/op
                 listUser·p1.00:   30.540 ms/op

Iteration   3: 5.104 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.417 ms/op
                 listUser·p0.50:   4.768 ms/op
                 listUser·p0.90:   6.152 ms/op
                 listUser·p0.95:   7.447 ms/op
                 listUser·p0.99:   10.125 ms/op
                 listUser·p0.999:  17.773 ms/op
                 listUser·p0.9999: 21.151 ms/op
                 listUser·p1.00:   22.020 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 185821
  mean =      5.158 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 115838 
    [ 5.000,  7.500) = 60306 
    [ 7.500, 10.000) = 7676 
    [10.000, 12.500) = 1292 
    [12.500, 15.000) = 234 
    [15.000, 17.500) = 122 
    [17.500, 20.000) = 85 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 77 
    [25.000, 27.500) = 78 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 23 
    [35.000, 37.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      2.146 ms/op
     p(50.0000) =      4.817 ms/op
     p(90.0000) =      6.291 ms/op
     p(95.0000) =      7.569 ms/op
     p(99.0000) =     10.142 ms/op
     p(99.9000) =     23.763 ms/op
     p(99.9900) =     34.396 ms/op
     p(99.9990) =     36.438 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.433 ± 4.461  ops/ms
ClientPb.existUser                       thrpt       3   7.613 ± 2.684  ops/ms
ClientPb.getUser                         thrpt       3   7.360 ± 4.617  ops/ms
ClientPb.listUser                        thrpt       3   6.410 ± 1.965  ops/ms
ClientPb.createUser                       avgt       3   4.210 ± 1.957   ms/op
ClientPb.existUser                        avgt       3   4.056 ± 0.583   ms/op
ClientPb.getUser                          avgt       3   4.266 ± 1.342   ms/op
ClientPb.listUser                         avgt       3   4.999 ± 0.165   ms/op
ClientPb.createUser                     sample  218007   4.401 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.483           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.125           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.530           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.586           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.831           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.936           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.161           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.865           ms/op
ClientPb.existUser                      sample  232083   4.135 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.497           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.932           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.932           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.841           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.159           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.416           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.883           ms/op
ClientPb.existUser:existUser·p1.00      sample          34.210           ms/op
ClientPb.getUser                        sample  230849   4.157 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.403           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.965           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.915           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.677           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.069           ms/op
ClientPb.getUser:getUser·p0.999         sample          21.271           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.259           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.080           ms/op
ClientPb.listUser                       sample  185821   5.158 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.146           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.817           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.291           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.569           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.142           ms/op
ClientPb.listUser:listUser·p0.999       sample          23.763           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.396           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.831           ms/op
