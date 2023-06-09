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
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 6.177 ops/ms
# Warmup Iteration   3: 8.870 ops/ms
Iteration   1: 9.734 ops/ms
Iteration   2: 10.276 ops/ms
Iteration   3: 9.568 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.859 ±(99.9%) 6.749 ops/ms [Average]
  (min, avg, max) = (9.568, 9.859, 10.276), stdev = 0.370
  CI (99.9%): [3.111, 16.608] (assumes normal distribution)


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
# Warmup Iteration   1: 3.207 ops/ms
# Warmup Iteration   2: 8.429 ops/ms
# Warmup Iteration   3: 9.905 ops/ms
Iteration   1: 10.663 ops/ms
Iteration   2: 10.061 ops/ms
Iteration   3: 10.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.265 ±(99.9%) 6.292 ops/ms [Average]
  (min, avg, max) = (10.061, 10.265, 10.663), stdev = 0.345
  CI (99.9%): [3.973, 16.557] (assumes normal distribution)


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
# Warmup Iteration   1: 3.202 ops/ms
# Warmup Iteration   2: 8.718 ops/ms
# Warmup Iteration   3: 9.383 ops/ms
Iteration   1: 10.081 ops/ms
Iteration   2: 10.166 ops/ms
Iteration   3: 10.089 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.112 ±(99.9%) 0.855 ops/ms [Average]
  (min, avg, max) = (10.081, 10.112, 10.166), stdev = 0.047
  CI (99.9%): [9.257, 10.967] (assumes normal distribution)


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
# Warmup Iteration   1: 3.185 ops/ms
# Warmup Iteration   2: 7.254 ops/ms
# Warmup Iteration   3: 7.991 ops/ms
Iteration   1: 7.981 ops/ms
Iteration   2: 8.510 ops/ms
Iteration   3: 8.366 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.286 ±(99.9%) 4.987 ops/ms [Average]
  (min, avg, max) = (7.981, 8.286, 8.510), stdev = 0.273
  CI (99.9%): [3.299, 13.273] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 8.639 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 3.560 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.292 ±(99.9%) 0.003 ms/op
Iteration   1: 3.241 ±(99.9%) 0.009 ms/op
Iteration   2: 3.282 ±(99.9%) 0.006 ms/op
Iteration   3: 3.093 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.205 ±(99.9%) 1.815 ms/op [Average]
  (min, avg, max) = (3.093, 3.205, 3.282), stdev = 0.099
  CI (99.9%): [1.390, 5.020] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.401 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.341 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.260 ±(99.9%) 0.004 ms/op
Iteration   1: 3.056 ±(99.9%) 0.003 ms/op
Iteration   2: 3.013 ±(99.9%) 0.006 ms/op
Iteration   3: 3.162 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.077 ±(99.9%) 1.396 ms/op [Average]
  (min, avg, max) = (3.013, 3.077, 3.162), stdev = 0.077
  CI (99.9%): [1.681, 4.473] (assumes normal distribution)


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
# Warmup Iteration   1: 8.472 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.376 ±(99.9%) 0.005 ms/op
Iteration   1: 3.217 ±(99.9%) 0.004 ms/op
Iteration   2: 3.246 ±(99.9%) 0.006 ms/op
Iteration   3: 3.123 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.195 ±(99.9%) 1.177 ms/op [Average]
  (min, avg, max) = (3.123, 3.195, 3.246), stdev = 0.065
  CI (99.9%): [2.019, 4.372] (assumes normal distribution)


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
# Warmup Iteration   1: 8.715 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 4.194 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.904 ±(99.9%) 0.007 ms/op
Iteration   1: 3.796 ±(99.9%) 0.010 ms/op
Iteration   2: 3.767 ±(99.9%) 0.010 ms/op
Iteration   3: 3.681 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.748 ±(99.9%) 1.091 ms/op [Average]
  (min, avg, max) = (3.681, 3.748, 3.796), stdev = 0.060
  CI (99.9%): [2.656, 4.839] (assumes normal distribution)


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
# Warmup Iteration   1: 7.653 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.589 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.208 ±(99.9%) 0.008 ms/op
Iteration   1: 3.289 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.240 ms/op
                 createUser·p0.90:   3.588 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   6.283 ms/op
                 createUser·p0.999:  11.338 ms/op
                 createUser·p0.9999: 21.823 ms/op
                 createUser·p1.00:   22.249 ms/op

Iteration   2: 3.215 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.536 ms/op
                 createUser·p0.50:   3.158 ms/op
                 createUser·p0.90:   3.592 ms/op
                 createUser·p0.95:   3.957 ms/op
                 createUser·p0.99:   5.603 ms/op
                 createUser·p0.999:  16.034 ms/op
                 createUser·p0.9999: 24.519 ms/op
                 createUser·p1.00:   25.002 ms/op

Iteration   3: 3.119 ±(99.9%) 0.006 ms/op
                 createUser·p0.00:   1.569 ms/op
                 createUser·p0.50:   3.133 ms/op
                 createUser·p0.90:   3.285 ms/op
                 createUser·p0.95:   3.469 ms/op
                 createUser·p0.99:   4.964 ms/op
                 createUser·p0.999:  14.644 ms/op
                 createUser·p0.9999: 19.816 ms/op
                 createUser·p1.00:   20.218 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 299131
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 25961 
    [ 2.500,  5.000) = 266360 
    [ 5.000,  7.500) = 6020 
    [ 7.500, 10.000) = 372 
    [10.000, 12.500) = 85 
    [12.500, 15.000) = 32 
    [15.000, 17.500) = 65 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 110 
    [22.500, 25.000) = 38 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.536 ms/op
     p(50.0000) =      3.178 ms/op
     p(90.0000) =      3.469 ms/op
     p(95.0000) =      3.834 ms/op
     p(99.0000) =      5.661 ms/op
     p(99.9000) =     15.188 ms/op
     p(99.9900) =     23.012 ms/op
     p(99.9990) =     24.937 ms/op
     p(99.9999) =     25.002 ms/op
    p(100.0000) =     25.002 ms/op


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
# Warmup Iteration   1: 7.563 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.482 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.091 ±(99.9%) 0.008 ms/op
Iteration   1: 3.071 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.251 ms/op
                 existUser·p0.50:   3.011 ms/op
                 existUser·p0.90:   3.318 ms/op
                 existUser·p0.95:   3.494 ms/op
                 existUser·p0.99:   5.136 ms/op
                 existUser·p0.999:  8.552 ms/op
                 existUser·p0.9999: 25.985 ms/op
                 existUser·p1.00:   26.771 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   0.945 ms/op
                 existUser·p0.50:   3.142 ms/op
                 existUser·p0.90:   3.305 ms/op
                 existUser·p0.95:   3.846 ms/op
                 existUser·p0.99:   5.292 ms/op
                 existUser·p0.999:  9.829 ms/op
                 existUser·p0.9999: 29.337 ms/op
                 existUser·p1.00:   29.622 ms/op

Iteration   3: 3.320 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.581 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.838 ms/op
                 existUser·p0.95:   4.219 ms/op
                 existUser·p0.99:   6.462 ms/op
                 existUser·p0.999:  14.123 ms/op
                 existUser·p0.9999: 20.829 ms/op
                 existUser·p1.00:   22.315 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 301931
  mean =      3.177 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18296 
    [ 2.500,  5.000) = 277950 
    [ 5.000,  7.500) = 4975 
    [ 7.500, 10.000) = 320 
    [10.000, 12.500) = 54 
    [12.500, 15.000) = 64 
    [15.000, 17.500) = 46 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 125 
    [22.500, 25.000) = 7 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      3.105 ms/op
     p(90.0000) =      3.564 ms/op
     p(95.0000) =      3.940 ms/op
     p(99.0000) =      5.669 ms/op
     p(99.9000) =     14.057 ms/op
     p(99.9900) =     27.512 ms/op
     p(99.9990) =     29.491 ms/op
     p(99.9999) =     29.622 ms/op
    p(100.0000) =     29.622 ms/op


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
# Warmup Iteration   1: 9.251 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.498 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.481 ±(99.9%) 0.010 ms/op
Iteration   1: 3.168 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.430 ms/op
                 getUser·p0.50:   3.080 ms/op
                 getUser·p0.90:   3.424 ms/op
                 getUser·p0.95:   3.621 ms/op
                 getUser·p0.99:   5.682 ms/op
                 getUser·p0.999:  19.106 ms/op
                 getUser·p0.9999: 29.065 ms/op
                 getUser·p1.00:   30.736 ms/op

Iteration   2: 3.149 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.858 ms/op
                 getUser·p0.50:   3.072 ms/op
                 getUser·p0.90:   3.396 ms/op
                 getUser·p0.95:   3.580 ms/op
                 getUser·p0.99:   5.341 ms/op
                 getUser·p0.999:  11.676 ms/op
                 getUser·p0.9999: 25.849 ms/op
                 getUser·p1.00:   27.001 ms/op

Iteration   3: 3.231 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.505 ms/op
                 getUser·p0.50:   3.166 ms/op
                 getUser·p0.90:   3.613 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.636 ms/op
                 getUser·p0.999:  9.241 ms/op
                 getUser·p0.9999: 20.454 ms/op
                 getUser·p1.00:   21.365 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 301370
  mean =      3.183 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12816 
    [ 2.500,  5.000) = 283755 
    [ 5.000,  7.500) = 3804 
    [ 7.500, 10.000) = 616 
    [10.000, 12.500) = 27 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 13 
    [17.500, 20.000) = 102 
    [20.000, 22.500) = 74 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 9 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.109 ms/op
     p(90.0000) =      3.486 ms/op
     p(95.0000) =      3.723 ms/op
     p(99.0000) =      5.587 ms/op
     p(99.9000) =     14.833 ms/op
     p(99.9900) =     27.296 ms/op
     p(99.9990) =     30.704 ms/op
     p(99.9999) =     30.736 ms/op
    p(100.0000) =     30.736 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.330 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 4.345 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.012 ms/op
Iteration   1: 3.909 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.276 ms/op
                 listUser·p0.50:   3.842 ms/op
                 listUser·p0.90:   4.202 ms/op
                 listUser·p0.95:   4.596 ms/op
                 listUser·p0.99:   6.939 ms/op
                 listUser·p0.999:  15.927 ms/op
                 listUser·p0.9999: 22.945 ms/op
                 listUser·p1.00:   23.527 ms/op

Iteration   2: 3.968 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.835 ms/op
                 listUser·p0.50:   3.805 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   7.881 ms/op
                 listUser·p0.999:  15.127 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   20.283 ms/op

Iteration   3: 3.827 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.372 ms/op
                 listUser·p0.50:   3.744 ms/op
                 listUser·p0.90:   4.071 ms/op
                 listUser·p0.95:   4.538 ms/op
                 listUser·p0.99:   7.487 ms/op
                 listUser·p0.999:  13.484 ms/op
                 listUser·p0.9999: 15.674 ms/op
                 listUser·p1.00:   16.204 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 246323
  mean =      3.900 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 237322 
    [ 5.000,  7.500) = 6644 
    [ 7.500, 10.000) = 1446 
    [10.000, 12.500) = 319 
    [12.500, 15.000) = 372 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 21 
    [20.000, 22.500) = 38 
    [22.500, 25.000) = 15 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.276 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.325 ms/op
     p(95.0000) =      4.686 ms/op
     p(99.0000) =      7.373 ms/op
     p(99.9000) =     14.320 ms/op
     p(99.9900) =     21.213 ms/op
     p(99.9990) =     23.205 ms/op
     p(99.9999) =     23.527 ms/op
    p(100.0000) =     23.527 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.859 ± 6.749  ops/ms
ClientPb.existUser                       thrpt       3  10.265 ± 6.292  ops/ms
ClientPb.getUser                         thrpt       3  10.112 ± 0.855  ops/ms
ClientPb.listUser                        thrpt       3   8.286 ± 4.987  ops/ms
ClientPb.createUser                       avgt       3   3.205 ± 1.815   ms/op
ClientPb.existUser                        avgt       3   3.077 ± 1.396   ms/op
ClientPb.getUser                          avgt       3   3.195 ± 1.177   ms/op
ClientPb.listUser                         avgt       3   3.748 ± 1.091   ms/op
ClientPb.createUser                     sample  299131   3.206 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.536           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.178           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.469           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.834           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.661           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.188           ms/op
ClientPb.createUser:createUser·p0.9999  sample          23.012           ms/op
ClientPb.createUser:createUser·p1.00    sample          25.002           ms/op
ClientPb.existUser                      sample  301931   3.177 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.945           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.105           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.564           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.940           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.669           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.057           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.512           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.622           ms/op
ClientPb.getUser                        sample  301370   3.183 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.430           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.109           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.486           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.723           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.587           ms/op
ClientPb.getUser:getUser·p0.999         sample          14.833           ms/op
ClientPb.getUser:getUser·p0.9999        sample          27.296           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.736           ms/op
ClientPb.listUser                       sample  246323   3.900 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.276           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.797           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.325           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.686           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.373           ms/op
ClientPb.listUser:listUser·p0.999       sample          14.320           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.213           ms/op
ClientPb.listUser:listUser·p1.00        sample          23.527           ms/op
