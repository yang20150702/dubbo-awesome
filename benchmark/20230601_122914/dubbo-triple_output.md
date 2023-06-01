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
# Warmup Iteration   1: 2.110 ops/ms
# Warmup Iteration   2: 5.802 ops/ms
# Warmup Iteration   3: 8.633 ops/ms
Iteration   1: 9.345 ops/ms
Iteration   2: 9.329 ops/ms
Iteration   3: 9.204 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.293 ±(99.9%) 1.410 ops/ms [Average]
  (min, avg, max) = (9.204, 9.293, 9.345), stdev = 0.077
  CI (99.9%): [7.883, 10.703] (assumes normal distribution)


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
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 8.999 ops/ms
# Warmup Iteration   3: 9.886 ops/ms
Iteration   1: 9.803 ops/ms
Iteration   2: 9.680 ops/ms
Iteration   3: 9.593 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.692 ±(99.9%) 1.920 ops/ms [Average]
  (min, avg, max) = (9.593, 9.692, 9.803), stdev = 0.105
  CI (99.9%): [7.772, 11.612] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 3.492 ops/ms
# Warmup Iteration   2: 8.656 ops/ms
# Warmup Iteration   3: 9.146 ops/ms
Iteration   1: 9.279 ops/ms
Iteration   2: 9.165 ops/ms
Iteration   3: 9.555 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.333 ±(99.9%) 3.658 ops/ms [Average]
  (min, avg, max) = (9.165, 9.333, 9.555), stdev = 0.201
  CI (99.9%): [5.675, 12.991] (assumes normal distribution)


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
# Warmup Iteration   1: 2.945 ops/ms
# Warmup Iteration   2: 7.392 ops/ms
# Warmup Iteration   3: 8.090 ops/ms
Iteration   1: 7.804 ops/ms
Iteration   2: 8.205 ops/ms
Iteration   3: 8.514 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.174 ±(99.9%) 6.492 ops/ms [Average]
  (min, avg, max) = (7.804, 8.174, 8.514), stdev = 0.356
  CI (99.9%): [1.682, 14.666] (assumes normal distribution)


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
# Warmup Iteration   1: 9.446 ±(99.9%) 0.027 ms/op
# Warmup Iteration   2: 3.926 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.687 ±(99.9%) 0.003 ms/op
Iteration   1: 3.413 ±(99.9%) 0.010 ms/op
Iteration   2: 3.502 ±(99.9%) 0.007 ms/op
Iteration   3: 3.289 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.401 ±(99.9%) 1.949 ms/op [Average]
  (min, avg, max) = (3.289, 3.401, 3.502), stdev = 0.107
  CI (99.9%): [1.452, 5.350] (assumes normal distribution)


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
# Warmup Iteration   1: 8.203 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.462 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.324 ±(99.9%) 0.004 ms/op
Iteration   1: 3.190 ±(99.9%) 0.013 ms/op
Iteration   2: 3.136 ±(99.9%) 0.010 ms/op
Iteration   3: 3.224 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.183 ±(99.9%) 0.815 ms/op [Average]
  (min, avg, max) = (3.136, 3.183, 3.224), stdev = 0.045
  CI (99.9%): [2.369, 3.998] (assumes normal distribution)


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
# Warmup Iteration   1: 7.963 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.704 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.468 ±(99.9%) 0.008 ms/op
Iteration   1: 3.386 ±(99.9%) 0.004 ms/op
Iteration   2: 3.396 ±(99.9%) 0.005 ms/op
Iteration   3: 3.528 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.437 ±(99.9%) 1.438 ms/op [Average]
  (min, avg, max) = (3.386, 3.437, 3.528), stdev = 0.079
  CI (99.9%): [1.999, 4.875] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.247 ±(99.9%) 0.044 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.988 ±(99.9%) 0.010 ms/op
Iteration   1: 3.930 ±(99.9%) 0.012 ms/op
Iteration   2: 3.891 ±(99.9%) 0.010 ms/op
Iteration   3: 3.866 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.896 ±(99.9%) 0.591 ms/op [Average]
  (min, avg, max) = (3.866, 3.896, 3.930), stdev = 0.032
  CI (99.9%): [3.305, 4.486] (assumes normal distribution)


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
# Warmup Iteration   1: 8.980 ±(99.9%) 0.112 ms/op
# Warmup Iteration   2: 4.001 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.488 ±(99.9%) 0.011 ms/op
Iteration   1: 3.355 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.638 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.797 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   5.480 ms/op
                 createUser·p0.999:  20.636 ms/op
                 createUser·p0.9999: 23.820 ms/op
                 createUser·p1.00:   25.264 ms/op

Iteration   2: 3.357 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.739 ms/op
                 createUser·p0.50:   3.211 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.067 ms/op
                 createUser·p0.99:   5.710 ms/op
                 createUser·p0.999:  23.560 ms/op
                 createUser·p0.9999: 26.082 ms/op
                 createUser·p1.00:   28.279 ms/op

Iteration   3: 3.336 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.114 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.727 ms/op
                 createUser·p0.95:   3.969 ms/op
                 createUser·p0.99:   4.694 ms/op
                 createUser·p0.999:  18.481 ms/op
                 createUser·p0.9999: 25.463 ms/op
                 createUser·p1.00:   26.313 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 286342
  mean =      3.349 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6035 
    [ 2.500,  5.000) = 276096 
    [ 5.000,  7.500) = 3276 
    [ 7.500, 10.000) = 540 
    [10.000, 12.500) = 66 
    [12.500, 15.000) = 13 
    [15.000, 17.500) = 9 
    [17.500, 20.000) = 42 
    [20.000, 22.500) = 68 
    [22.500, 25.000) = 135 
    [25.000, 27.500) = 61 

  Percentiles, ms/op:
      p(0.0000) =      1.114 ms/op
     p(50.0000) =      3.228 ms/op
     p(90.0000) =      3.768 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      5.472 ms/op
     p(99.9000) =     18.546 ms/op
     p(99.9900) =     25.723 ms/op
     p(99.9990) =     27.063 ms/op
     p(99.9999) =     28.279 ms/op
    p(100.0000) =     28.279 ms/op


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
# Warmup Iteration   1: 8.549 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.507 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.305 ±(99.9%) 0.008 ms/op
Iteration   1: 3.325 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.346 ms/op
                 existUser·p0.50:   3.178 ms/op
                 existUser·p0.90:   3.637 ms/op
                 existUser·p0.95:   3.957 ms/op
                 existUser·p0.99:   6.332 ms/op
                 existUser·p0.999:  19.287 ms/op
                 existUser·p0.9999: 27.144 ms/op
                 existUser·p1.00:   27.722 ms/op

Iteration   2: 3.386 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.057 ms/op
                 existUser·p0.50:   3.260 ms/op
                 existUser·p0.90:   3.781 ms/op
                 existUser·p0.95:   4.174 ms/op
                 existUser·p0.99:   6.071 ms/op
                 existUser·p0.999:  21.140 ms/op
                 existUser·p0.9999: 26.396 ms/op
                 existUser·p1.00:   28.377 ms/op

Iteration   3: 3.319 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.495 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   4.055 ms/op
                 existUser·p0.99:   5.734 ms/op
                 existUser·p0.999:  17.633 ms/op
                 existUser·p0.9999: 25.133 ms/op
                 existUser·p1.00:   25.625 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 287024
  mean =      3.343 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8842 
    [ 2.500,  5.000) = 271048 
    [ 5.000,  7.500) = 5890 
    [ 7.500, 10.000) = 801 
    [10.000, 12.500) = 121 
    [12.500, 15.000) = 29 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 72 
    [22.500, 25.000) = 102 
    [25.000, 27.500) = 80 

  Percentiles, ms/op:
      p(0.0000) =      1.057 ms/op
     p(50.0000) =      3.236 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.076 ms/op
     p(99.0000) =      6.046 ms/op
     p(99.9000) =     18.542 ms/op
     p(99.9900) =     26.159 ms/op
     p(99.9990) =     27.494 ms/op
     p(99.9999) =     28.377 ms/op
    p(100.0000) =     28.377 ms/op


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
# Warmup Iteration   1: 8.316 ±(99.9%) 0.105 ms/op
# Warmup Iteration   2: 3.579 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.484 ±(99.9%) 0.011 ms/op
Iteration   1: 3.638 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.733 ms/op
                 getUser·p0.50:   3.404 ms/op
                 getUser·p0.90:   4.424 ms/op
                 getUser·p0.95:   4.940 ms/op
                 getUser·p0.99:   6.758 ms/op
                 getUser·p0.999:  16.941 ms/op
                 getUser·p0.9999: 22.650 ms/op
                 getUser·p1.00:   22.970 ms/op

Iteration   2: 3.317 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.599 ms/op
                 getUser·p0.50:   3.248 ms/op
                 getUser·p0.90:   3.727 ms/op
                 getUser·p0.95:   4.071 ms/op
                 getUser·p0.99:   5.112 ms/op
                 getUser·p0.999:  17.559 ms/op
                 getUser·p0.9999: 25.997 ms/op
                 getUser·p1.00:   27.165 ms/op

Iteration   3: 3.395 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.206 ms/op
                 getUser·p0.50:   3.277 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  20.897 ms/op
                 getUser·p0.9999: 32.297 ms/op
                 getUser·p1.00:   32.899 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 278429
  mean =      3.445 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9762 
    [ 2.500,  5.000) = 261027 
    [ 5.000,  7.500) = 6413 
    [ 7.500, 10.000) = 701 
    [10.000, 12.500) = 144 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 64 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 119 
    [22.500, 25.000) = 83 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.206 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.973 ms/op
     p(95.0000) =      4.489 ms/op
     p(99.0000) =      6.125 ms/op
     p(99.9000) =     20.414 ms/op
     p(99.9900) =     30.835 ms/op
     p(99.9990) =     32.815 ms/op
     p(99.9999) =     32.899 ms/op
    p(100.0000) =     32.899 ms/op


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
# Warmup Iteration   1: 10.802 ±(99.9%) 0.145 ms/op
# Warmup Iteration   2: 4.770 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 4.043 ±(99.9%) 0.013 ms/op
Iteration   1: 3.999 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.528 ms/op
                 listUser·p0.50:   3.838 ms/op
                 listUser·p0.90:   4.334 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   7.684 ms/op
                 listUser·p0.999:  21.951 ms/op
                 listUser·p0.9999: 25.460 ms/op
                 listUser·p1.00:   26.182 ms/op

Iteration   2: 3.934 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.567 ms/op
                 listUser·p0.50:   3.867 ms/op
                 listUser·p0.90:   4.096 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   6.839 ms/op
                 listUser·p0.999:  15.364 ms/op
                 listUser·p0.9999: 18.858 ms/op
                 listUser·p1.00:   22.544 ms/op

Iteration   3: 3.955 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   3.863 ms/op
                 listUser·p0.90:   4.538 ms/op
                 listUser·p0.95:   4.850 ms/op
                 listUser·p0.99:   6.799 ms/op
                 listUser·p0.999:  14.254 ms/op
                 listUser·p0.9999: 22.542 ms/op
                 listUser·p1.00:   22.577 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 242165
  mean =      3.963 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 234510 
    [ 5.000,  7.500) = 5494 
    [ 7.500, 10.000) = 1226 
    [10.000, 12.500) = 287 
    [12.500, 15.000) = 190 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 69 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      1.528 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.342 ms/op
     p(95.0000) =      4.719 ms/op
     p(99.0000) =      7.119 ms/op
     p(99.9000) =     16.657 ms/op
     p(99.9900) =     24.850 ms/op
     p(99.9990) =     25.921 ms/op
     p(99.9999) =     26.182 ms/op
    p(100.0000) =     26.182 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.293 ± 1.410  ops/ms
ClientPb.existUser                       thrpt       3   9.692 ± 1.920  ops/ms
ClientPb.getUser                         thrpt       3   9.333 ± 3.658  ops/ms
ClientPb.listUser                        thrpt       3   8.174 ± 6.492  ops/ms
ClientPb.createUser                       avgt       3   3.401 ± 1.949   ms/op
ClientPb.existUser                        avgt       3   3.183 ± 0.815   ms/op
ClientPb.getUser                          avgt       3   3.437 ± 1.438   ms/op
ClientPb.listUser                         avgt       3   3.896 ± 0.591   ms/op
ClientPb.createUser                     sample  286342   3.349 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.114           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.228           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.472           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.546           ms/op
ClientPb.createUser:createUser·p0.9999  sample          25.723           ms/op
ClientPb.createUser:createUser·p1.00    sample          28.279           ms/op
ClientPb.existUser                      sample  287024   3.343 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.057           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.236           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.076           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.046           ms/op
ClientPb.existUser:existUser·p0.999     sample          18.542           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.159           ms/op
ClientPb.existUser:existUser·p1.00      sample          28.377           ms/op
ClientPb.getUser                        sample  278429   3.445 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.206           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.314           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.973           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.489           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.125           ms/op
ClientPb.getUser:getUser·p0.999         sample          20.414           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.835           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.899           ms/op
ClientPb.listUser                       sample  242165   3.963 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.528           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.342           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.719           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.119           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.657           ms/op
ClientPb.listUser:listUser·p0.9999      sample          24.850           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.182           ms/op
