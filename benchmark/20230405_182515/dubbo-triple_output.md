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
# Warmup Iteration   1: 2.284 ops/ms
# Warmup Iteration   2: 5.858 ops/ms
# Warmup Iteration   3: 8.778 ops/ms
Iteration   1: 9.280 ops/ms
Iteration   2: 9.352 ops/ms
Iteration   3: 9.732 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.455 ±(99.9%) 4.432 ops/ms [Average]
  (min, avg, max) = (9.280, 9.455, 9.732), stdev = 0.243
  CI (99.9%): [5.023, 13.886] (assumes normal distribution)


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
# Warmup Iteration   1: 3.517 ops/ms
# Warmup Iteration   2: 8.783 ops/ms
# Warmup Iteration   3: 9.013 ops/ms
Iteration   1: 9.898 ops/ms
Iteration   2: 9.363 ops/ms
Iteration   3: 9.364 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.542 ±(99.9%) 5.623 ops/ms [Average]
  (min, avg, max) = (9.363, 9.542, 9.898), stdev = 0.308
  CI (99.9%): [3.918, 15.165] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 3.103 ops/ms
# Warmup Iteration   2: 7.668 ops/ms
# Warmup Iteration   3: 9.175 ops/ms
Iteration   1: 9.243 ops/ms
Iteration   2: 9.782 ops/ms
Iteration   3: 9.603 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.543 ±(99.9%) 5.012 ops/ms [Average]
  (min, avg, max) = (9.243, 9.543, 9.782), stdev = 0.275
  CI (99.9%): [4.531, 14.555] (assumes normal distribution)


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
# Warmup Iteration   1: 2.841 ops/ms
# Warmup Iteration   2: 6.858 ops/ms
# Warmup Iteration   3: 8.003 ops/ms
Iteration   1: 8.145 ops/ms
Iteration   2: 7.833 ops/ms
Iteration   3: 8.279 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.086 ±(99.9%) 4.176 ops/ms [Average]
  (min, avg, max) = (7.833, 8.086, 8.279), stdev = 0.229
  CI (99.9%): [3.910, 12.261] (assumes normal distribution)


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
# Warmup Iteration   1: 9.503 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.814 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.543 ±(99.9%) 0.008 ms/op
Iteration   1: 3.499 ±(99.9%) 0.008 ms/op
Iteration   2: 3.342 ±(99.9%) 0.011 ms/op
Iteration   3: 3.259 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.367 ±(99.9%) 2.228 ms/op [Average]
  (min, avg, max) = (3.259, 3.367, 3.499), stdev = 0.122
  CI (99.9%): [1.139, 5.594] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:39
# Fork: 1 of 1
# Warmup Iteration   1: 7.359 ±(99.9%) 0.015 ms/op
# Warmup Iteration   2: 3.493 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.007 ms/op
Iteration   1: 3.189 ±(99.9%) 0.007 ms/op
Iteration   2: 3.361 ±(99.9%) 0.007 ms/op
Iteration   3: 3.160 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.237 ±(99.9%) 1.974 ms/op [Average]
  (min, avg, max) = (3.160, 3.237, 3.361), stdev = 0.108
  CI (99.9%): [1.263, 5.211] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:33
# Fork: 1 of 1
# Warmup Iteration   1: 9.014 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 3.604 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.474 ±(99.9%) 0.006 ms/op
Iteration   1: 3.422 ±(99.9%) 0.004 ms/op
Iteration   2: 3.367 ±(99.9%) 0.006 ms/op
Iteration   3: 3.444 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.411 ±(99.9%) 0.728 ms/op [Average]
  (min, avg, max) = (3.367, 3.411, 3.444), stdev = 0.040
  CI (99.9%): [2.683, 4.139] (assumes normal distribution)


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
# Warmup Iteration   1: 10.298 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 4.311 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.101 ±(99.9%) 0.004 ms/op
Iteration   1: 3.833 ±(99.9%) 0.014 ms/op
Iteration   2: 3.784 ±(99.9%) 0.011 ms/op
Iteration   3: 3.947 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.855 ±(99.9%) 1.529 ms/op [Average]
  (min, avg, max) = (3.784, 3.855, 3.947), stdev = 0.084
  CI (99.9%): [2.326, 5.384] (assumes normal distribution)


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
# Warmup Iteration   1: 8.340 ±(99.9%) 0.111 ms/op
# Warmup Iteration   2: 3.893 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.435 ±(99.9%) 0.009 ms/op
Iteration   1: 3.298 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.683 ms/op
                 createUser·p0.50:   3.314 ms/op
                 createUser·p0.90:   3.523 ms/op
                 createUser·p0.95:   3.777 ms/op
                 createUser·p0.99:   4.817 ms/op
                 createUser·p0.999:  9.806 ms/op
                 createUser·p0.9999: 28.525 ms/op
                 createUser·p1.00:   29.262 ms/op

Iteration   2: 3.470 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.039 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.985 ms/op
                 createUser·p0.95:   4.506 ms/op
                 createUser·p0.99:   6.480 ms/op
                 createUser·p0.999:  20.408 ms/op
                 createUser·p0.9999: 24.248 ms/op
                 createUser·p1.00:   25.559 ms/op

Iteration   3: 3.399 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.321 ms/op
                 createUser·p0.50:   3.265 ms/op
                 createUser·p0.90:   3.838 ms/op
                 createUser·p0.95:   4.309 ms/op
                 createUser·p0.99:   5.956 ms/op
                 createUser·p0.999:  16.723 ms/op
                 createUser·p0.9999: 23.973 ms/op
                 createUser·p1.00:   25.297 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 283263
  mean =      3.388 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11311 
    [ 2.500,  5.000) = 265539 
    [ 5.000,  7.500) = 5441 
    [ 7.500, 10.000) = 621 
    [10.000, 12.500) = 58 
    [12.500, 15.000) = 5 
    [15.000, 17.500) = 15 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 88 
    [22.500, 25.000) = 133 
    [25.000, 27.500) = 9 

  Percentiles, ms/op:
      p(0.0000) =      1.039 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.797 ms/op
     p(95.0000) =      4.174 ms/op
     p(99.0000) =      5.898 ms/op
     p(99.9000) =     16.825 ms/op
     p(99.9900) =     27.308 ms/op
     p(99.9990) =     29.142 ms/op
     p(99.9999) =     29.262 ms/op
    p(100.0000) =     29.262 ms/op


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
# Warmup Iteration   1: 8.178 ±(99.9%) 0.109 ms/op
# Warmup Iteration   2: 3.556 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.229 ±(99.9%) 0.008 ms/op
Iteration   1: 3.188 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   0.892 ms/op
                 existUser·p0.50:   3.084 ms/op
                 existUser·p0.90:   3.473 ms/op
                 existUser·p0.95:   4.030 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  8.380 ms/op
                 existUser·p0.9999: 24.237 ms/op
                 existUser·p1.00:   25.723 ms/op

Iteration   2: 3.262 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.675 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.703 ms/op
                 existUser·p0.95:   4.080 ms/op
                 existUser·p0.99:   5.751 ms/op
                 existUser·p0.999:  10.903 ms/op
                 existUser·p0.9999: 24.117 ms/op
                 existUser·p1.00:   25.821 ms/op

Iteration   3: 3.239 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.341 ms/op
                 existUser·p0.50:   3.138 ms/op
                 existUser·p0.90:   3.551 ms/op
                 existUser·p0.95:   3.830 ms/op
                 existUser·p0.99:   5.505 ms/op
                 existUser·p0.999:  10.292 ms/op
                 existUser·p0.9999: 28.942 ms/op
                 existUser·p1.00:   30.409 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 297354
  mean =      3.229 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8284 
    [ 2.500,  5.000) = 284072 
    [ 5.000,  7.500) = 4250 
    [ 7.500, 10.000) = 446 
    [10.000, 12.500) = 46 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 8 
    [17.500, 20.000) = 24 
    [20.000, 22.500) = 55 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 17 
    [27.500, 30.000) = 28 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.113 ms/op
     p(90.0000) =      3.588 ms/op
     p(95.0000) =      3.990 ms/op
     p(99.0000) =      5.530 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     27.599 ms/op
     p(99.9990) =     29.922 ms/op
     p(99.9999) =     30.409 ms/op
    p(100.0000) =     30.409 ms/op


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
# Warmup Iteration   1: 8.555 ±(99.9%) 0.103 ms/op
# Warmup Iteration   2: 3.686 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.534 ±(99.9%) 0.012 ms/op
Iteration   1: 3.490 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.481 ms/op
                 getUser·p0.50:   3.293 ms/op
                 getUser·p0.90:   4.051 ms/op
                 getUser·p0.95:   5.259 ms/op
                 getUser·p0.99:   6.668 ms/op
                 getUser·p0.999:  19.399 ms/op
                 getUser·p0.9999: 22.766 ms/op
                 getUser·p1.00:   23.855 ms/op

Iteration   2: 3.247 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.786 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.596 ms/op
                 getUser·p0.95:   3.932 ms/op
                 getUser·p0.99:   5.215 ms/op
                 getUser·p0.999:  9.945 ms/op
                 getUser·p0.9999: 24.816 ms/op
                 getUser·p1.00:   25.297 ms/op

Iteration   3: 3.368 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.073 ms/op
                 getUser·p0.50:   3.269 ms/op
                 getUser·p0.90:   3.805 ms/op
                 getUser·p0.95:   4.235 ms/op
                 getUser·p0.99:   5.767 ms/op
                 getUser·p0.999:  20.895 ms/op
                 getUser·p0.9999: 26.870 ms/op
                 getUser·p1.00:   27.263 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 285233
  mean =      3.365 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15470 
    [ 2.500,  5.000) = 260278 
    [ 5.000,  7.500) = 8484 
    [ 7.500, 10.000) = 571 
    [10.000, 12.500) = 118 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 11 
    [17.500, 20.000) = 11 
    [20.000, 22.500) = 101 
    [22.500, 25.000) = 119 
    [25.000, 27.500) = 58 

  Percentiles, ms/op:
      p(0.0000) =      1.073 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.830 ms/op
     p(95.0000) =      4.342 ms/op
     p(99.0000) =      6.054 ms/op
     p(99.9000) =     19.300 ms/op
     p(99.9900) =     25.754 ms/op
     p(99.9990) =     27.230 ms/op
     p(99.9999) =     27.263 ms/op
    p(100.0000) =     27.263 ms/op


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
# Warmup Iteration   1: 9.272 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.318 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.990 ±(99.9%) 0.013 ms/op
Iteration   1: 3.983 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.231 ms/op
                 listUser·p0.50:   3.834 ms/op
                 listUser·p0.90:   4.694 ms/op
                 listUser·p0.95:   5.046 ms/op
                 listUser·p0.99:   6.930 ms/op
                 listUser·p0.999:  18.995 ms/op
                 listUser·p0.9999: 24.115 ms/op
                 listUser·p1.00:   25.068 ms/op

Iteration   2: 3.988 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.388 ms/op
                 listUser·p0.50:   3.891 ms/op
                 listUser·p0.90:   4.514 ms/op
                 listUser·p0.95:   4.891 ms/op
                 listUser·p0.99:   6.595 ms/op
                 listUser·p0.999:  15.352 ms/op
                 listUser·p0.9999: 21.137 ms/op
                 listUser·p1.00:   21.365 ms/op

Iteration   3: 3.963 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.425 ms/op
                 listUser·p0.50:   3.826 ms/op
                 listUser·p0.90:   4.268 ms/op
                 listUser·p0.95:   4.489 ms/op
                 listUser·p0.99:   7.217 ms/op
                 listUser·p0.999:  12.849 ms/op
                 listUser·p0.9999: 15.430 ms/op
                 listUser·p1.00:   15.565 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 241261
  mean =      3.978 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 56 
    [ 2.500,  5.000) = 230861 
    [ 5.000,  7.500) = 8575 
    [ 7.500, 10.000) = 1061 
    [10.000, 12.500) = 274 
    [12.500, 15.000) = 133 
    [15.000, 17.500) = 145 
    [17.500, 20.000) = 101 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      1.231 ms/op
     p(50.0000) =      3.863 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.891 ms/op
     p(99.0000) =      6.865 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     21.627 ms/op
     p(99.9990) =     25.008 ms/op
     p(99.9999) =     25.068 ms/op
    p(100.0000) =     25.068 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.455 ± 4.432  ops/ms
ClientPb.existUser                       thrpt       3   9.542 ± 5.623  ops/ms
ClientPb.getUser                         thrpt       3   9.543 ± 5.012  ops/ms
ClientPb.listUser                        thrpt       3   8.086 ± 4.176  ops/ms
ClientPb.createUser                       avgt       3   3.367 ± 2.228   ms/op
ClientPb.existUser                        avgt       3   3.237 ± 1.974   ms/op
ClientPb.getUser                          avgt       3   3.411 ± 0.728   ms/op
ClientPb.listUser                         avgt       3   3.855 ± 1.529   ms/op
ClientPb.createUser                     sample  283263   3.388 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.039           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.297           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.174           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.898           ms/op
ClientPb.createUser:createUser·p0.999   sample          16.825           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.308           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.262           ms/op
ClientPb.existUser                      sample  297354   3.229 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.892           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.113           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.588           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.990           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.011           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.599           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.409           ms/op
ClientPb.getUser                        sample  285233   3.365 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.073           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.244           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.830           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.342           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.054           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.300           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.754           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.263           ms/op
ClientPb.listUser                       sample  241261   3.978 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.231           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.863           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.432           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.891           ms/op
ClientPb.listUser:listUser·p0.99        sample           6.865           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.483           ms/op
ClientPb.listUser:listUser·p0.9999      sample          21.627           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.068           ms/op
