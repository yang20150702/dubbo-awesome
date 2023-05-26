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
# Warmup Iteration   1: 2.367 ops/ms
# Warmup Iteration   2: 6.160 ops/ms
# Warmup Iteration   3: 9.007 ops/ms
Iteration   1: 9.705 ops/ms
Iteration   2: 9.874 ops/ms
Iteration   3: 9.685 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.755 ±(99.9%) 1.896 ops/ms [Average]
  (min, avg, max) = (9.685, 9.755, 9.874), stdev = 0.104
  CI (99.9%): [7.859, 11.650] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 3.074 ops/ms
# Warmup Iteration   2: 9.034 ops/ms
# Warmup Iteration   3: 9.630 ops/ms
Iteration   1: 9.617 ops/ms
Iteration   2: 10.392 ops/ms
Iteration   3: 9.909 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.973 ±(99.9%) 7.143 ops/ms [Average]
  (min, avg, max) = (9.617, 9.973, 10.392), stdev = 0.392
  CI (99.9%): [2.830, 17.116] (assumes normal distribution)


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
# Warmup Iteration   1: 3.425 ops/ms
# Warmup Iteration   2: 8.741 ops/ms
# Warmup Iteration   3: 9.536 ops/ms
Iteration   1: 9.893 ops/ms
Iteration   2: 9.799 ops/ms
Iteration   3: 10.112 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.935 ±(99.9%) 2.938 ops/ms [Average]
  (min, avg, max) = (9.799, 9.935, 10.112), stdev = 0.161
  CI (99.9%): [6.996, 12.873] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.026 ops/ms
# Warmup Iteration   2: 7.419 ops/ms
# Warmup Iteration   3: 8.167 ops/ms
Iteration   1: 8.302 ops/ms
Iteration   2: 8.339 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.385 ±(99.9%) 2.067 ops/ms [Average]
  (min, avg, max) = (8.302, 8.385, 8.514), stdev = 0.113
  CI (99.9%): [6.318, 10.452] (assumes normal distribution)


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
# Warmup Iteration   1: 8.151 ±(99.9%) 0.049 ms/op
# Warmup Iteration   2: 3.928 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.504 ±(99.9%) 0.006 ms/op
Iteration   1: 3.397 ±(99.9%) 0.006 ms/op
Iteration   2: 3.167 ±(99.9%) 0.009 ms/op
Iteration   3: 3.416 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.327 ±(99.9%) 2.536 ms/op [Average]
  (min, avg, max) = (3.167, 3.327, 3.416), stdev = 0.139
  CI (99.9%): [0.790, 5.863] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.490 ±(99.9%) 0.045 ms/op
# Warmup Iteration   2: 3.546 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.139 ±(99.9%) 0.006 ms/op
Iteration   1: 3.355 ±(99.9%) 0.007 ms/op
Iteration   2: 3.240 ±(99.9%) 0.006 ms/op
Iteration   3: 3.207 ±(99.9%) 0.001 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.267 ±(99.9%) 1.418 ms/op [Average]
  (min, avg, max) = (3.207, 3.267, 3.355), stdev = 0.078
  CI (99.9%): [1.849, 4.686] (assumes normal distribution)


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
# Warmup Iteration   1: 8.498 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.585 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.299 ±(99.9%) 0.005 ms/op
Iteration   1: 3.218 ±(99.9%) 0.001 ms/op
Iteration   2: 3.168 ±(99.9%) 0.006 ms/op
Iteration   3: 3.269 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.219 ±(99.9%) 0.921 ms/op [Average]
  (min, avg, max) = (3.168, 3.219, 3.269), stdev = 0.050
  CI (99.9%): [2.297, 4.140] (assumes normal distribution)


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
# Warmup Iteration   1: 10.025 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 4.117 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.925 ±(99.9%) 0.003 ms/op
Iteration   1: 3.729 ±(99.9%) 0.012 ms/op
Iteration   2: 3.779 ±(99.9%) 0.013 ms/op
Iteration   3: 3.717 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.742 ±(99.9%) 0.603 ms/op [Average]
  (min, avg, max) = (3.717, 3.742, 3.779), stdev = 0.033
  CI (99.9%): [3.138, 4.345] (assumes normal distribution)


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
# Warmup Iteration   1: 9.180 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.868 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.323 ±(99.9%) 0.009 ms/op
Iteration   1: 3.402 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.147 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.936 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  17.138 ms/op
                 createUser·p0.9999: 19.929 ms/op
                 createUser·p1.00:   20.251 ms/op

Iteration   2: 3.175 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.241 ms/op
                 createUser·p0.50:   3.060 ms/op
                 createUser·p0.90:   3.580 ms/op
                 createUser·p0.95:   3.772 ms/op
                 createUser·p0.99:   4.882 ms/op
                 createUser·p0.999:  19.126 ms/op
                 createUser·p0.9999: 22.673 ms/op
                 createUser·p1.00:   23.233 ms/op

Iteration   3: 3.208 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.981 ms/op
                 createUser·p0.50:   3.047 ms/op
                 createUser·p0.90:   3.617 ms/op
                 createUser·p0.95:   4.260 ms/op
                 createUser·p0.99:   5.596 ms/op
                 createUser·p0.999:  18.033 ms/op
                 createUser·p0.9999: 28.574 ms/op
                 createUser·p1.00:   29.557 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 294350
  mean =      3.259 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9533 
    [ 2.500,  5.000) = 279038 
    [ 5.000,  7.500) = 4985 
    [ 7.500, 10.000) = 422 
    [10.000, 12.500) = 20 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 26 
    [17.500, 20.000) = 181 
    [20.000, 22.500) = 97 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      0.981 ms/op
     p(50.0000) =      3.121 ms/op
     p(90.0000) =      3.740 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.562 ms/op
     p(99.9000) =     17.924 ms/op
     p(99.9900) =     27.460 ms/op
     p(99.9990) =     29.248 ms/op
     p(99.9999) =     29.557 ms/op
    p(100.0000) =     29.557 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 7.353 ±(99.9%) 0.091 ms/op
# Warmup Iteration   2: 3.377 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.126 ±(99.9%) 0.007 ms/op
Iteration   1: 3.070 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.509 ms/op
                 existUser·p0.50:   2.990 ms/op
                 existUser·p0.90:   3.273 ms/op
                 existUser·p0.95:   3.478 ms/op
                 existUser·p0.99:   5.399 ms/op
                 existUser·p0.999:  14.238 ms/op
                 existUser·p0.9999: 22.249 ms/op
                 existUser·p1.00:   23.364 ms/op

Iteration   2: 3.069 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.370 ms/op
                 existUser·p0.50:   2.978 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.441 ms/op
                 existUser·p0.99:   4.850 ms/op
                 existUser·p0.999:  14.295 ms/op
                 existUser·p0.9999: 24.281 ms/op
                 existUser·p1.00:   24.969 ms/op

Iteration   3: 3.088 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.401 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.228 ms/op
                 existUser·p0.95:   3.572 ms/op
                 existUser·p0.99:   5.317 ms/op
                 existUser·p0.999:  10.361 ms/op
                 existUser·p0.9999: 20.555 ms/op
                 existUser·p1.00:   21.201 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 312098
  mean =      3.075 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12059 
    [ 2.500,  5.000) = 295889 
    [ 5.000,  7.500) = 3268 
    [ 7.500, 10.000) = 420 
    [10.000, 12.500) = 102 
    [12.500, 15.000) = 68 
    [15.000, 17.500) = 68 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 127 
    [22.500, 25.000) = 55 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      2.994 ms/op
     p(90.0000) =      3.260 ms/op
     p(95.0000) =      3.478 ms/op
     p(99.0000) =      5.333 ms/op
     p(99.9000) =     14.221 ms/op
     p(99.9900) =     23.298 ms/op
     p(99.9990) =     24.647 ms/op
     p(99.9999) =     24.969 ms/op
    p(100.0000) =     24.969 ms/op


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
# Warmup Iteration   1: 8.326 ±(99.9%) 0.095 ms/op
# Warmup Iteration   2: 3.629 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.379 ±(99.9%) 0.011 ms/op
Iteration   1: 3.179 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.421 ms/op
                 getUser·p0.50:   3.060 ms/op
                 getUser·p0.90:   3.445 ms/op
                 getUser·p0.95:   3.748 ms/op
                 getUser·p0.99:   6.341 ms/op
                 getUser·p0.999:  10.600 ms/op
                 getUser·p0.9999: 22.825 ms/op
                 getUser·p1.00:   25.330 ms/op

Iteration   2: 3.207 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.005 ms/op
                 getUser·p0.50:   3.129 ms/op
                 getUser·p0.90:   3.535 ms/op
                 getUser·p0.95:   3.895 ms/op
                 getUser·p0.99:   5.808 ms/op
                 getUser·p0.999:  10.282 ms/op
                 getUser·p0.9999: 28.739 ms/op
                 getUser·p1.00:   29.229 ms/op

Iteration   3: 3.214 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.399 ms/op
                 getUser·p0.50:   3.158 ms/op
                 getUser·p0.90:   3.527 ms/op
                 getUser·p0.95:   3.723 ms/op
                 getUser·p0.99:   5.652 ms/op
                 getUser·p0.999:  13.786 ms/op
                 getUser·p0.9999: 22.611 ms/op
                 getUser·p1.00:   23.429 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 299654
  mean =      3.200 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11972 
    [ 2.500,  5.000) = 282478 
    [ 5.000,  7.500) = 4111 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 108 
    [12.500, 15.000) = 58 
    [15.000, 17.500) = 4 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 109 
    [22.500, 25.000) = 42 
    [25.000, 27.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.005 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.506 ms/op
     p(95.0000) =      3.781 ms/op
     p(99.0000) =      5.874 ms/op
     p(99.9000) =     13.375 ms/op
     p(99.9900) =     27.232 ms/op
     p(99.9990) =     28.869 ms/op
     p(99.9999) =     29.229 ms/op
    p(100.0000) =     29.229 ms/op


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
# Warmup Iteration   1: 9.752 ±(99.9%) 0.127 ms/op
# Warmup Iteration   2: 4.220 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.769 ±(99.9%) 0.011 ms/op
Iteration   1: 3.833 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.573 ms/op
                 listUser·p0.50:   3.666 ms/op
                 listUser·p0.90:   4.219 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.143 ms/op
                 listUser·p0.999:  15.696 ms/op
                 listUser·p0.9999: 21.474 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   2: 3.805 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.756 ms/op
                 listUser·p0.90:   4.108 ms/op
                 listUser·p0.95:   4.465 ms/op
                 listUser·p0.99:   6.611 ms/op
                 listUser·p0.999:  13.812 ms/op
                 listUser·p0.9999: 14.516 ms/op
                 listUser·p1.00:   15.745 ms/op

Iteration   3: 3.762 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.277 ms/op
                 listUser·p0.50:   3.670 ms/op
                 listUser·p0.90:   3.908 ms/op
                 listUser·p0.95:   4.235 ms/op
                 listUser·p0.99:   7.283 ms/op
                 listUser·p0.999:  13.615 ms/op
                 listUser·p0.9999: 18.809 ms/op
                 listUser·p1.00:   18.940 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 252408
  mean =      3.800 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 37 
    [ 2.500,  5.000) = 243873 
    [ 5.000,  7.500) = 6552 
    [ 7.500, 10.000) = 1171 
    [10.000, 12.500) = 227 
    [12.500, 15.000) = 391 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.573 ms/op
     p(50.0000) =      3.711 ms/op
     p(90.0000) =      4.092 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      7.086 ms/op
     p(99.9000) =     14.460 ms/op
     p(99.9900) =     20.636 ms/op
     p(99.9990) =     22.445 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.755 ± 1.896  ops/ms
ClientPb.existUser                       thrpt       3   9.973 ± 7.143  ops/ms
ClientPb.getUser                         thrpt       3   9.935 ± 2.938  ops/ms
ClientPb.listUser                        thrpt       3   8.385 ± 2.067  ops/ms
ClientPb.createUser                       avgt       3   3.327 ± 2.536   ms/op
ClientPb.existUser                        avgt       3   3.267 ± 1.418   ms/op
ClientPb.getUser                          avgt       3   3.219 ± 0.921   ms/op
ClientPb.listUser                         avgt       3   3.742 ± 0.603   ms/op
ClientPb.createUser                     sample  294350   3.259 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.981           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.121           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.740           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.562           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.924           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.460           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.557           ms/op
ClientPb.existUser                      sample  312098   3.075 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.370           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.994           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.260           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.478           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.333           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.221           ms/op
ClientPb.existUser:existUser·p0.9999    sample          23.298           ms/op
ClientPb.existUser:existUser·p1.00      sample          24.969           ms/op
ClientPb.getUser                        sample  299654   3.200 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.005           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.506           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.781           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.874           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.375           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.232           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.229           ms/op
ClientPb.listUser                       sample  252408   3.800 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.573           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.711           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.092           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.473           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.086           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.460           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.636           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.577           ms/op
