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
# Warmup Iteration   1: 2.021 ops/ms
# Warmup Iteration   2: 4.702 ops/ms
# Warmup Iteration   3: 8.318 ops/ms
Iteration   1: 8.694 ops/ms
Iteration   2: 9.199 ops/ms
Iteration   3: 9.144 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.012 ±(99.9%) 5.056 ops/ms [Average]
  (min, avg, max) = (8.694, 9.012, 9.199), stdev = 0.277
  CI (99.9%): [3.956, 14.069] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.014 ops/ms
# Warmup Iteration   2: 9.009 ops/ms
# Warmup Iteration   3: 9.489 ops/ms
Iteration   1: 10.122 ops/ms
Iteration   2: 9.871 ops/ms
Iteration   3: 9.639 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.877 ±(99.9%) 4.408 ops/ms [Average]
  (min, avg, max) = (9.639, 9.877, 10.122), stdev = 0.242
  CI (99.9%): [5.469, 14.285] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 2.923 ops/ms
# Warmup Iteration   2: 7.766 ops/ms
# Warmup Iteration   3: 8.958 ops/ms
Iteration   1: 9.167 ops/ms
Iteration   2: 8.793 ops/ms
Iteration   3: 9.353 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.104 ±(99.9%) 5.199 ops/ms [Average]
  (min, avg, max) = (8.793, 9.104, 9.353), stdev = 0.285
  CI (99.9%): [3.906, 14.303] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.416 ops/ms
# Warmup Iteration   2: 7.037 ops/ms
# Warmup Iteration   3: 7.907 ops/ms
Iteration   1: 7.872 ops/ms
Iteration   2: 7.985 ops/ms
Iteration   3: 8.171 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.009 ±(99.9%) 2.756 ops/ms [Average]
  (min, avg, max) = (7.872, 8.009, 8.171), stdev = 0.151
  CI (99.9%): [5.253, 10.765] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 10.632 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.890 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.499 ±(99.9%) 0.009 ms/op
Iteration   1: 3.477 ±(99.9%) 0.003 ms/op
Iteration   2: 3.422 ±(99.9%) 0.006 ms/op
Iteration   3: 3.516 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.471 ±(99.9%) 0.863 ms/op [Average]
  (min, avg, max) = (3.422, 3.471, 3.516), stdev = 0.047
  CI (99.9%): [2.608, 4.335] (assumes normal distribution)


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
# Warmup Iteration   1: 9.633 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.470 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.443 ±(99.9%) 0.008 ms/op
Iteration   1: 3.393 ±(99.9%) 0.006 ms/op
Iteration   2: 3.201 ±(99.9%) 0.013 ms/op
Iteration   3: 3.241 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.278 ±(99.9%) 1.849 ms/op [Average]
  (min, avg, max) = (3.201, 3.278, 3.393), stdev = 0.101
  CI (99.9%): [1.429, 5.127] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 11.037 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 3.990 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.390 ±(99.9%) 0.004 ms/op
Iteration   1: 3.299 ±(99.9%) 0.008 ms/op
Iteration   2: 3.430 ±(99.9%) 0.006 ms/op
Iteration   3: 3.401 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.377 ±(99.9%) 1.256 ms/op [Average]
  (min, avg, max) = (3.299, 3.377, 3.430), stdev = 0.069
  CI (99.9%): [2.121, 4.632] (assumes normal distribution)


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
# Warmup Iteration   1: 11.872 ±(99.9%) 0.055 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.009 ms/op
Iteration   1: 4.041 ±(99.9%) 0.005 ms/op
Iteration   2: 3.951 ±(99.9%) 0.014 ms/op
Iteration   3: 4.019 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.003 ±(99.9%) 0.856 ms/op [Average]
  (min, avg, max) = (3.951, 4.003, 4.041), stdev = 0.047
  CI (99.9%): [3.147, 4.859] (assumes normal distribution)


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
# Warmup Iteration   1: 10.376 ±(99.9%) 0.149 ms/op
# Warmup Iteration   2: 3.815 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.768 ±(99.9%) 0.015 ms/op
Iteration   1: 3.371 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.636 ms/op
                 createUser·p0.50:   3.252 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.039 ms/op
                 createUser·p0.99:   5.833 ms/op
                 createUser·p0.999:  19.448 ms/op
                 createUser·p0.9999: 25.855 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 3.462 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.169 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   6.062 ms/op
                 createUser·p0.999:  21.568 ms/op
                 createUser·p0.9999: 24.372 ms/op
                 createUser·p1.00:   25.592 ms/op

Iteration   3: 3.410 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.376 ms/op
                 createUser·p0.50:   3.318 ms/op
                 createUser·p0.90:   3.903 ms/op
                 createUser·p0.95:   4.174 ms/op
                 createUser·p0.99:   5.620 ms/op
                 createUser·p0.999:  12.931 ms/op
                 createUser·p0.9999: 26.988 ms/op
                 createUser·p1.00:   28.475 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 281074
  mean =      3.414 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5229 
    [ 2.500,  5.000) = 270811 
    [ 5.000,  7.500) = 4025 
    [ 7.500, 10.000) = 519 
    [10.000, 12.500) = 197 
    [12.500, 15.000) = 37 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 13 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 89 
    [25.000, 27.500) = 53 

  Percentiles, ms/op:
      p(0.0000) =      1.169 ms/op
     p(50.0000) =      3.293 ms/op
     p(90.0000) =      3.895 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.849 ms/op
     p(99.9000) =     13.303 ms/op
     p(99.9900) =     25.880 ms/op
     p(99.9990) =     27.728 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


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
# Warmup Iteration   1: 9.728 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 3.608 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.357 ±(99.9%) 0.010 ms/op
Iteration   1: 3.294 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.556 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.535 ms/op
                 existUser·p0.95:   3.899 ms/op
                 existUser·p0.99:   5.748 ms/op
                 existUser·p0.999:  13.264 ms/op
                 existUser·p0.9999: 23.317 ms/op
                 existUser·p1.00:   25.297 ms/op

Iteration   2: 3.326 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.252 ms/op
                 existUser·p0.90:   3.613 ms/op
                 existUser·p0.95:   3.928 ms/op
                 existUser·p0.99:   5.980 ms/op
                 existUser·p0.999:  21.712 ms/op
                 existUser·p0.9999: 26.280 ms/op
                 existUser·p1.00:   26.804 ms/op

Iteration   3: 3.402 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.365 ms/op
                 existUser·p0.50:   3.338 ms/op
                 existUser·p0.90:   3.744 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   6.674 ms/op
                 existUser·p0.999:  11.289 ms/op
                 existUser·p0.9999: 26.517 ms/op
                 existUser·p1.00:   27.951 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287095
  mean =      3.340 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18303 
    [ 2.500,  5.000) = 263107 
    [ 5.000,  7.500) = 4259 
    [ 7.500, 10.000) = 879 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 94 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 91 
    [22.500, 25.000) = 96 
    [25.000, 27.500) = 69 

  Percentiles, ms/op:
      p(0.0000) =      0.365 ms/op
     p(50.0000) =      3.289 ms/op
     p(90.0000) =      3.625 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      6.005 ms/op
     p(99.9000) =     13.976 ms/op
     p(99.9900) =     26.191 ms/op
     p(99.9990) =     26.851 ms/op
     p(99.9999) =     27.951 ms/op
    p(100.0000) =     27.951 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.642 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.828 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.583 ±(99.9%) 0.012 ms/op
Iteration   1: 3.452 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.338 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.596 ms/op
                 getUser·p0.99:   6.767 ms/op
                 getUser·p0.999:  19.333 ms/op
                 getUser·p0.9999: 24.838 ms/op
                 getUser·p1.00:   25.395 ms/op

Iteration   2: 3.303 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.552 ms/op
                 getUser·p0.50:   3.236 ms/op
                 getUser·p0.90:   3.654 ms/op
                 getUser·p0.95:   3.924 ms/op
                 getUser·p0.99:   5.720 ms/op
                 getUser·p0.999:  12.972 ms/op
                 getUser·p0.9999: 26.116 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.547 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   0.635 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.084 ms/op
                 getUser·p0.95:   4.473 ms/op
                 getUser·p0.99:   6.590 ms/op
                 getUser·p0.999:  19.816 ms/op
                 getUser·p0.9999: 37.485 ms/op
                 getUser·p1.00:   41.288 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 279925
  mean =      3.431 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 271932 
    [ 5.000, 10.000) = 7499 
    [10.000, 15.000) = 206 
    [15.000, 20.000) = 31 
    [20.000, 25.000) = 171 
    [25.000, 30.000) = 64 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 16 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.635 ms/op
     p(50.0000) =      3.330 ms/op
     p(90.0000) =      3.924 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.357 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     29.360 ms/op
     p(99.9990) =     41.288 ms/op
     p(99.9999) =     41.288 ms/op
    p(100.0000) =     41.288 ms/op


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
# Warmup Iteration   1: 11.460 ±(99.9%) 0.140 ms/op
# Warmup Iteration   2: 4.383 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.133 ±(99.9%) 0.012 ms/op
Iteration   1: 4.054 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   2.249 ms/op
                 listUser·p0.50:   3.875 ms/op
                 listUser·p0.90:   4.342 ms/op
                 listUser·p0.95:   5.136 ms/op
                 listUser·p0.99:   7.545 ms/op
                 listUser·p0.999:  24.838 ms/op
                 listUser·p0.9999: 27.368 ms/op
                 listUser·p1.00:   28.475 ms/op

Iteration   2: 4.052 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.343 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.522 ms/op
                 listUser·p0.95:   4.833 ms/op
                 listUser·p0.99:   7.328 ms/op
                 listUser·p0.999:  16.936 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   22.905 ms/op

Iteration   3: 4.030 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.052 ms/op
                 listUser·p0.50:   3.879 ms/op
                 listUser·p0.90:   4.596 ms/op
                 listUser·p0.95:   4.989 ms/op
                 listUser·p0.99:   7.717 ms/op
                 listUser·p0.999:  15.887 ms/op
                 listUser·p0.9999: 17.662 ms/op
                 listUser·p1.00:   17.695 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 237458
  mean =      4.045 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 226007 
    [ 5.000,  7.500) = 8956 
    [ 7.500, 10.000) = 1638 
    [10.000, 12.500) = 241 
    [12.500, 15.000) = 155 
    [15.000, 17.500) = 220 
    [17.500, 20.000) = 53 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 57 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      2.052 ms/op
     p(50.0000) =      3.879 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.545 ms/op
     p(99.9000) =     17.286 ms/op
     p(99.9900) =     26.673 ms/op
     p(99.9990) =     28.234 ms/op
     p(99.9999) =     28.475 ms/op
    p(100.0000) =     28.475 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.012 ± 5.056  ops/ms
ClientPb.existUser                       thrpt       3   9.877 ± 4.408  ops/ms
ClientPb.getUser                         thrpt       3   9.104 ± 5.199  ops/ms
ClientPb.listUser                        thrpt       3   8.009 ± 2.756  ops/ms
ClientPb.createUser                       avgt       3   3.471 ± 0.863   ms/op
ClientPb.existUser                        avgt       3   3.278 ± 1.849   ms/op
ClientPb.getUser                          avgt       3   3.377 ± 1.256   ms/op
ClientPb.listUser                         avgt       3   4.003 ± 0.856   ms/op
ClientPb.createUser                     sample  281074   3.414 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.169           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.293           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.895           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.849           ms/op
ClientPb.createUser:createUser·p0.999   sample          13.303           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.880           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.475           ms/op
ClientPb.existUser                      sample  287095   3.340 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.365           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.289           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.625           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.005           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.976           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.191           ms/op
ClientPb.existUser:existUser·p1.00      sample          27.951           ms/op
ClientPb.getUser                        sample  279925   3.431 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.635           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.330           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.924           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.357           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.366           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.360           ms/op
ClientPb.getUser:getUser·p1.00          sample          41.288           ms/op
ClientPb.listUser                       sample  237458   4.045 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.052           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.879           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.948           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.545           ms/op
ClientPb.listUser:listUser·p0.999       sample          17.286           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.673           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.475           ms/op
