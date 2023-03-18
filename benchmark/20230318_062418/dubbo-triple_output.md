# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.259 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 8.724 ops/ms
Iteration   1: 9.676 ops/ms
Iteration   2: 9.640 ops/ms
Iteration   3: 9.585 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.634 ±(99.9%) 0.840 ops/ms [Average]
  (min, avg, max) = (9.585, 9.634, 9.676), stdev = 0.046
  CI (99.9%): [8.794, 10.474] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.330 ops/ms
# Warmup Iteration   2: 9.135 ops/ms
# Warmup Iteration   3: 9.542 ops/ms
Iteration   1: 9.950 ops/ms
Iteration   2: 9.814 ops/ms
Iteration   3: 10.122 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.962 ±(99.9%) 2.809 ops/ms [Average]
  (min, avg, max) = (9.814, 9.962, 10.122), stdev = 0.154
  CI (99.9%): [7.153, 12.771] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.749 ops/ms
# Warmup Iteration   2: 7.967 ops/ms
# Warmup Iteration   3: 9.459 ops/ms
Iteration   1: 9.029 ops/ms
Iteration   2: 9.686 ops/ms
Iteration   3: 9.545 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.420 ±(99.9%) 6.307 ops/ms [Average]
  (min, avg, max) = (9.029, 9.420, 9.686), stdev = 0.346
  CI (99.9%): [3.113, 15.727] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:51
# Fork: 1 of 1
# Warmup Iteration   1: 2.903 ops/ms
# Warmup Iteration   2: 6.890 ops/ms
# Warmup Iteration   3: 7.983 ops/ms
Iteration   1: 8.076 ops/ms
Iteration   2: 8.069 ops/ms
Iteration   3: 8.047 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.064 ±(99.9%) 0.270 ops/ms [Average]
  (min, avg, max) = (8.047, 8.064, 8.076), stdev = 0.015
  CI (99.9%): [7.794, 8.334] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 10.921 ±(99.9%) 0.041 ms/op
# Warmup Iteration   2: 4.043 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.482 ±(99.9%) 0.003 ms/op
Iteration   1: 3.344 ±(99.9%) 0.009 ms/op
Iteration   2: 3.426 ±(99.9%) 0.010 ms/op
Iteration   3: 3.392 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.387 ±(99.9%) 0.757 ms/op [Average]
  (min, avg, max) = (3.344, 3.387, 3.426), stdev = 0.041
  CI (99.9%): [2.630, 4.144] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 7.885 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.620 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.398 ±(99.9%) 0.004 ms/op
Iteration   1: 3.253 ±(99.9%) 0.009 ms/op
Iteration   2: 3.173 ±(99.9%) 0.006 ms/op
Iteration   3: 3.286 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.237 ±(99.9%) 1.058 ms/op [Average]
  (min, avg, max) = (3.173, 3.237, 3.286), stdev = 0.058
  CI (99.9%): [2.179, 4.295] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.770 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.783 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.460 ±(99.9%) 0.004 ms/op
Iteration   1: 3.581 ±(99.9%) 0.004 ms/op
Iteration   2: 3.303 ±(99.9%) 0.006 ms/op
Iteration   3: 3.307 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.397 ±(99.9%) 2.909 ms/op [Average]
  (min, avg, max) = (3.303, 3.397, 3.581), stdev = 0.159
  CI (99.9%): [0.488, 6.306] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 10.208 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.157 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.011 ms/op
Iteration   1: 3.879 ±(99.9%) 0.010 ms/op
Iteration   2: 3.833 ±(99.9%) 0.015 ms/op
Iteration   3: 3.922 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.878 ±(99.9%) 0.817 ms/op [Average]
  (min, avg, max) = (3.833, 3.878, 3.922), stdev = 0.045
  CI (99.9%): [3.061, 4.695] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 10.020 ±(99.9%) 0.113 ms/op
# Warmup Iteration   2: 4.109 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.427 ±(99.9%) 0.010 ms/op
Iteration   1: 3.444 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.370 ms/op
                 createUser·p0.50:   3.375 ms/op
                 createUser·p0.90:   3.842 ms/op
                 createUser·p0.95:   4.219 ms/op
                 createUser·p0.99:   6.545 ms/op
                 createUser·p0.999:  19.441 ms/op
                 createUser·p0.9999: 22.470 ms/op
                 createUser·p1.00:   23.658 ms/op

Iteration   2: 3.471 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.167 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.916 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.139 ms/op
                 createUser·p0.999:  22.506 ms/op
                 createUser·p0.9999: 38.914 ms/op
                 createUser·p1.00:   39.453 ms/op

Iteration   3: 3.444 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.673 ms/op
                 createUser·p0.50:   3.367 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.252 ms/op
                 createUser·p0.99:   5.800 ms/op
                 createUser·p0.999:  15.325 ms/op
                 createUser·p0.9999: 26.123 ms/op
                 createUser·p1.00:   26.935 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 277529
  mean =      3.453 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9940 
    [ 2.500,  5.000) = 261164 
    [ 5.000,  7.500) = 5084 
    [ 7.500, 10.000) = 724 
    [10.000, 12.500) = 172 
    [12.500, 15.000) = 107 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 29 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.167 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      3.883 ms/op
     p(95.0000) =      4.219 ms/op
     p(99.0000) =      6.038 ms/op
     p(99.9000) =     16.908 ms/op
     p(99.9900) =     38.142 ms/op
     p(99.9990) =     39.322 ms/op
     p(99.9999) =     39.453 ms/op
    p(100.0000) =     39.453 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 9.021 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.301 ±(99.9%) 0.008 ms/op
Iteration   1: 3.157 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.097 ms/op
                 existUser·p0.90:   3.367 ms/op
                 existUser·p0.95:   3.596 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  11.463 ms/op
                 existUser·p0.9999: 22.413 ms/op
                 existUser·p1.00:   22.970 ms/op

Iteration   2: 3.216 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.124 ms/op
                 existUser·p0.50:   3.170 ms/op
                 existUser·p0.90:   3.531 ms/op
                 existUser·p0.95:   3.715 ms/op
                 existUser·p0.99:   4.268 ms/op
                 existUser·p0.999:  14.096 ms/op
                 existUser·p0.9999: 34.738 ms/op
                 existUser·p1.00:   35.848 ms/op

Iteration   3: 3.246 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.358 ms/op
                 existUser·p0.50:   3.228 ms/op
                 existUser·p0.90:   3.445 ms/op
                 existUser·p0.95:   3.801 ms/op
                 existUser·p0.99:   5.423 ms/op
                 existUser·p0.999:  14.498 ms/op
                 existUser·p0.9999: 25.439 ms/op
                 existUser·p1.00:   26.673 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 299460
  mean =      3.206 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17409 
    [ 2.500,  5.000) = 278978 
    [ 5.000,  7.500) = 2186 
    [ 7.500, 10.000) = 337 
    [10.000, 12.500) = 195 
    [12.500, 15.000) = 93 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 18 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 29 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 26 
    [35.000, 37.500) = 6 

  Percentiles, ms/op:
      p(0.0000) =      1.124 ms/op
     p(50.0000) =      3.174 ms/op
     p(90.0000) =      3.457 ms/op
     p(95.0000) =      3.703 ms/op
     p(99.0000) =      5.087 ms/op
     p(99.9000) =     14.075 ms/op
     p(99.9900) =     33.755 ms/op
     p(99.9990) =     35.260 ms/op
     p(99.9999) =     35.848 ms/op
    p(100.0000) =     35.848 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 8.561 ±(99.9%) 0.120 ms/op
# Warmup Iteration   2: 3.809 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.487 ±(99.9%) 0.009 ms/op
Iteration   1: 3.429 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.837 ms/op
                 getUser·p0.50:   3.281 ms/op
                 getUser·p0.90:   3.719 ms/op
                 getUser·p0.95:   3.998 ms/op
                 getUser·p0.99:   6.980 ms/op
                 getUser·p0.999:  20.340 ms/op
                 getUser·p0.9999: 22.643 ms/op
                 getUser·p1.00:   24.084 ms/op

Iteration   2: 3.424 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.313 ms/op
                 getUser·p0.50:   3.351 ms/op
                 getUser·p0.90:   3.883 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  21.844 ms/op
                 getUser·p0.9999: 25.679 ms/op
                 getUser·p1.00:   26.280 ms/op

Iteration   3: 3.410 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.436 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   3.756 ms/op
                 getUser·p0.95:   4.041 ms/op
                 getUser·p0.99:   6.276 ms/op
                 getUser·p0.999:  15.662 ms/op
                 getUser·p0.9999: 35.496 ms/op
                 getUser·p1.00:   36.700 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 280429
  mean =      3.421 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6643 
    [ 2.500,  5.000) = 266380 
    [ 5.000,  7.500) = 6088 
    [ 7.500, 10.000) = 717 
    [10.000, 12.500) = 188 
    [12.500, 15.000) = 47 
    [15.000, 17.500) = 79 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 74 
    [25.000, 27.500) = 25 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.313 ms/op
     p(50.0000) =      3.305 ms/op
     p(90.0000) =      3.785 ms/op
     p(95.0000) =      4.108 ms/op
     p(99.0000) =      6.193 ms/op
     p(99.9000) =     19.356 ms/op
     p(99.9900) =     34.283 ms/op
     p(99.9990) =     36.700 ms/op
     p(99.9999) =     36.700 ms/op
    p(100.0000) =     36.700 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_362, OpenJDK 64-Bit Server VM, 25.362-b09
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.362-9/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.477 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 4.388 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.212 ±(99.9%) 0.014 ms/op
Iteration   1: 3.971 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.638 ms/op
                 listUser·p0.50:   3.793 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   7.315 ms/op
                 listUser·p0.999:  19.986 ms/op
                 listUser·p0.9999: 25.821 ms/op
                 listUser·p1.00:   26.214 ms/op

Iteration   2: 3.935 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.706 ms/op
                 listUser·p0.50:   3.772 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.735 ms/op
                 listUser·p0.99:   7.356 ms/op
                 listUser·p0.999:  15.679 ms/op
                 listUser·p0.9999: 17.719 ms/op
                 listUser·p1.00:   18.678 ms/op

Iteration   3: 3.900 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.310 ms/op
                 listUser·p0.50:   3.764 ms/op
                 listUser·p0.90:   4.489 ms/op
                 listUser·p0.95:   4.768 ms/op
                 listUser·p0.99:   6.829 ms/op
                 listUser·p0.999:  15.811 ms/op
                 listUser·p0.9999: 17.170 ms/op
                 listUser·p1.00:   17.334 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243952
  mean =      3.935 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 50 
    [ 2.500,  5.000) = 234741 
    [ 5.000,  7.500) = 7017 
    [ 7.500, 10.000) = 1530 
    [10.000, 12.500) = 132 
    [12.500, 15.000) = 102 
    [15.000, 17.500) = 234 
    [17.500, 20.000) = 66 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 15 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.772 ms/op
     p(90.0000) =      4.440 ms/op
     p(95.0000) =      4.801 ms/op
     p(99.0000) =      7.209 ms/op
     p(99.9000) =     16.171 ms/op
     p(99.9900) =     23.600 ms/op
     p(99.9990) =     26.102 ms/op
     p(99.9999) =     26.214 ms/op
    p(100.0000) =     26.214 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.634 ± 0.840  ops/ms
ClientPb.existUser                       thrpt       3   9.962 ± 2.809  ops/ms
ClientPb.getUser                         thrpt       3   9.420 ± 6.307  ops/ms
ClientPb.listUser                        thrpt       3   8.064 ± 0.270  ops/ms
ClientPb.createUser                       avgt       3   3.387 ± 0.757   ms/op
ClientPb.existUser                        avgt       3   3.237 ± 1.058   ms/op
ClientPb.getUser                          avgt       3   3.397 ± 2.909   ms/op
ClientPb.listUser                         avgt       3   3.878 ± 0.817   ms/op
ClientPb.createUser                     sample  277529   3.453 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.167           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.363           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.883           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.219           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.038           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.908           ms/op
ClientPb.createUser:createUser·p0.9999  sample          38.142           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.453           ms/op
ClientPb.existUser                      sample  299460   3.206 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.124           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.174           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.457           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.087           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.075           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.755           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.848           ms/op
ClientPb.getUser                        sample  280429   3.421 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.313           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.305           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.785           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.108           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.193           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.356           ms/op
ClientPb.getUser:getUser·p0.9999        sample          34.283           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.700           ms/op
ClientPb.listUser                       sample  243952   3.935 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.638           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.772           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.440           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.209           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.171           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.600           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.214           ms/op
