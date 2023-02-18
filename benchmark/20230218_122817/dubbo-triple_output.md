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
# Warmup Iteration   1: 2.123 ops/ms
# Warmup Iteration   2: 5.973 ops/ms
# Warmup Iteration   3: 8.783 ops/ms
Iteration   1: 9.475 ops/ms
Iteration   2: 9.434 ops/ms
Iteration   3: 9.462 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.457 ±(99.9%) 0.385 ops/ms [Average]
  (min, avg, max) = (9.434, 9.457, 9.475), stdev = 0.021
  CI (99.9%): [9.072, 9.842] (assumes normal distribution)


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
# Warmup Iteration   1: 2.994 ops/ms
# Warmup Iteration   2: 9.089 ops/ms
# Warmup Iteration   3: 9.283 ops/ms
Iteration   1: 9.714 ops/ms
Iteration   2: 10.228 ops/ms
Iteration   3: 9.613 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.852 ±(99.9%) 6.017 ops/ms [Average]
  (min, avg, max) = (9.613, 9.852, 10.228), stdev = 0.330
  CI (99.9%): [3.835, 15.869] (assumes normal distribution)


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
# Warmup Iteration   1: 2.997 ops/ms
# Warmup Iteration   2: 8.428 ops/ms
# Warmup Iteration   3: 9.257 ops/ms
Iteration   1: 9.620 ops/ms
Iteration   2: 9.195 ops/ms
Iteration   3: 9.218 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.344 ±(99.9%) 4.364 ops/ms [Average]
  (min, avg, max) = (9.195, 9.344, 9.620), stdev = 0.239
  CI (99.9%): [4.981, 13.708] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 2.980 ops/ms
# Warmup Iteration   2: 7.331 ops/ms
# Warmup Iteration   3: 8.156 ops/ms
Iteration   1: 7.779 ops/ms
Iteration   2: 8.319 ops/ms
Iteration   3: 8.203 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.100 ±(99.9%) 5.187 ops/ms [Average]
  (min, avg, max) = (7.779, 8.100, 8.319), stdev = 0.284
  CI (99.9%): [2.913, 13.287] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 9.366 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 3.672 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.467 ±(99.9%) 0.009 ms/op
Iteration   1: 3.356 ±(99.9%) 0.011 ms/op
Iteration   2: 3.399 ±(99.9%) 0.010 ms/op
Iteration   3: 3.422 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.393 ±(99.9%) 0.611 ms/op [Average]
  (min, avg, max) = (3.356, 3.393, 3.422), stdev = 0.034
  CI (99.9%): [2.781, 4.004] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.936 ±(99.9%) 0.033 ms/op
# Warmup Iteration   2: 3.502 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.262 ±(99.9%) 0.006 ms/op
Iteration   1: 3.231 ±(99.9%) 0.003 ms/op
Iteration   2: 3.264 ±(99.9%) 0.006 ms/op
Iteration   3: 3.251 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.249 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.231, 3.249, 3.264), stdev = 0.017
  CI (99.9%): [2.945, 3.552] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 8.991 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.726 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.569 ±(99.9%) 0.004 ms/op
Iteration   1: 3.413 ±(99.9%) 0.005 ms/op
Iteration   2: 3.323 ±(99.9%) 0.007 ms/op
Iteration   3: 3.336 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.357 ±(99.9%) 0.884 ms/op [Average]
  (min, avg, max) = (3.323, 3.357, 3.413), stdev = 0.048
  CI (99.9%): [2.473, 4.241] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 11.834 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.393 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.056 ±(99.9%) 0.006 ms/op
Iteration   1: 3.801 ±(99.9%) 0.010 ms/op
Iteration   2: 3.907 ±(99.9%) 0.010 ms/op
Iteration   3: 3.987 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.898 ±(99.9%) 1.701 ms/op [Average]
  (min, avg, max) = (3.801, 3.898, 3.987), stdev = 0.093
  CI (99.9%): [2.198, 5.599] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 10.632 ±(99.9%) 0.139 ms/op
# Warmup Iteration   2: 3.931 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.609 ±(99.9%) 0.012 ms/op
Iteration   1: 3.425 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.468 ms/op
                 createUser·p0.50:   3.228 ms/op
                 createUser·p0.90:   3.949 ms/op
                 createUser·p0.95:   4.407 ms/op
                 createUser·p0.99:   6.218 ms/op
                 createUser·p0.999:  19.057 ms/op
                 createUser·p0.9999: 26.334 ms/op
                 createUser·p1.00:   26.935 ms/op

Iteration   2: 3.450 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.116 ms/op
                 createUser·p0.50:   3.256 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.997 ms/op
                 createUser·p0.999:  21.340 ms/op
                 createUser·p0.9999: 25.100 ms/op
                 createUser·p1.00:   26.706 ms/op

Iteration   3: 3.461 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   0.844 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.994 ms/op
                 createUser·p0.95:   4.276 ms/op
                 createUser·p0.99:   5.767 ms/op
                 createUser·p0.999:  13.837 ms/op
                 createUser·p0.9999: 27.927 ms/op
                 createUser·p1.00:   29.131 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278650
  mean =      3.445 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4464 
    [ 2.500,  5.000) = 266787 
    [ 5.000,  7.500) = 6437 
    [ 7.500, 10.000) = 572 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 40 
    [15.000, 17.500) = 20 
    [17.500, 20.000) = 7 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 122 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      0.844 ms/op
     p(50.0000) =      3.260 ms/op
     p(90.0000) =      3.981 ms/op
     p(95.0000) =      4.309 ms/op
     p(99.0000) =      6.013 ms/op
     p(99.9000) =     14.336 ms/op
     p(99.9900) =     26.678 ms/op
     p(99.9990) =     29.014 ms/op
     p(99.9999) =     29.131 ms/op
    p(100.0000) =     29.131 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 9.127 ±(99.9%) 0.118 ms/op
# Warmup Iteration   2: 3.702 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.359 ±(99.9%) 0.009 ms/op
Iteration   1: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.180 ms/op
                 existUser·p0.50:   3.187 ms/op
                 existUser·p0.90:   3.756 ms/op
                 existUser·p0.95:   4.096 ms/op
                 existUser·p0.99:   5.415 ms/op
                 existUser·p0.999:  18.138 ms/op
                 existUser·p0.9999: 23.101 ms/op
                 existUser·p1.00:   25.592 ms/op

Iteration   2: 3.311 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.397 ms/op
                 existUser·p0.50:   3.191 ms/op
                 existUser·p0.90:   3.707 ms/op
                 existUser·p0.95:   4.026 ms/op
                 existUser·p0.99:   5.825 ms/op
                 existUser·p0.999:  16.481 ms/op
                 existUser·p0.9999: 25.767 ms/op
                 existUser·p1.00:   26.411 ms/op

Iteration   3: 3.312 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.462 ms/op
                 existUser·p0.50:   3.314 ms/op
                 existUser·p0.90:   3.502 ms/op
                 existUser·p0.95:   3.875 ms/op
                 existUser·p0.99:   5.308 ms/op
                 existUser·p0.999:  9.022 ms/op
                 existUser·p0.9999: 27.077 ms/op
                 existUser·p1.00:   29.786 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 289464
  mean =      3.318 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15027 
    [ 2.500,  5.000) = 269960 
    [ 5.000,  7.500) = 3493 
    [ 7.500, 10.000) = 499 
    [10.000, 12.500) = 183 
    [12.500, 15.000) = 46 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 98 
    [22.500, 25.000) = 99 
    [25.000, 27.500) = 51 

  Percentiles, ms/op:
      p(0.0000) =      1.180 ms/op
     p(50.0000) =      3.265 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      3.998 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     12.861 ms/op
     p(99.9900) =     26.182 ms/op
     p(99.9990) =     29.472 ms/op
     p(99.9999) =     29.786 ms/op
    p(100.0000) =     29.786 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 9.818 ±(99.9%) 0.122 ms/op
# Warmup Iteration   2: 3.797 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 3.558 ±(99.9%) 0.012 ms/op
Iteration   1: 3.637 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.536 ms/op
                 getUser·p0.50:   3.449 ms/op
                 getUser·p0.90:   4.157 ms/op
                 getUser·p0.95:   4.956 ms/op
                 getUser·p0.99:   6.969 ms/op
                 getUser·p0.999:  20.478 ms/op
                 getUser·p0.9999: 29.497 ms/op
                 getUser·p1.00:   30.999 ms/op

Iteration   2: 3.461 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.458 ms/op
                 getUser·p0.50:   3.359 ms/op
                 getUser·p0.90:   3.817 ms/op
                 getUser·p0.95:   4.174 ms/op
                 getUser·p0.99:   5.784 ms/op
                 getUser·p0.999:  9.332 ms/op
                 getUser·p0.9999: 24.233 ms/op
                 getUser·p1.00:   25.690 ms/op

Iteration   3: 3.534 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   0.746 ms/op
                 getUser·p0.50:   3.424 ms/op
                 getUser·p0.90:   4.137 ms/op
                 getUser·p0.95:   4.653 ms/op
                 getUser·p0.99:   6.463 ms/op
                 getUser·p0.999:  22.857 ms/op
                 getUser·p0.9999: 26.213 ms/op
                 getUser·p1.00:   26.706 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 270892
  mean =      3.543 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 9097 
    [ 2.500,  5.000) = 250887 
    [ 5.000,  7.500) = 9802 
    [ 7.500, 10.000) = 667 
    [10.000, 12.500) = 69 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 49 
    [17.500, 20.000) = 38 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 111 
    [25.000, 27.500) = 24 
    [27.500, 30.000) = 35 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.746 ms/op
     p(50.0000) =      3.412 ms/op
     p(90.0000) =      4.030 ms/op
     p(95.0000) =      4.669 ms/op
     p(99.0000) =      6.463 ms/op
     p(99.9000) =     18.973 ms/op
     p(99.9900) =     28.639 ms/op
     p(99.9990) =     30.952 ms/op
     p(99.9999) =     30.999 ms/op
    p(100.0000) =     30.999 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 11.361 ±(99.9%) 0.148 ms/op
# Warmup Iteration   2: 4.459 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 4.217 ±(99.9%) 0.015 ms/op
Iteration   1: 3.976 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   0.919 ms/op
                 listUser·p0.50:   3.850 ms/op
                 listUser·p0.90:   4.284 ms/op
                 listUser·p0.95:   4.506 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  18.631 ms/op
                 listUser·p0.9999: 22.675 ms/op
                 listUser·p1.00:   24.084 ms/op

Iteration   2: 4.021 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.403 ms/op
                 listUser·p0.50:   3.801 ms/op
                 listUser·p0.90:   4.456 ms/op
                 listUser·p0.95:   4.841 ms/op
                 listUser·p0.99:   7.658 ms/op
                 listUser·p0.999:  14.320 ms/op
                 listUser·p0.9999: 16.944 ms/op
                 listUser·p1.00:   17.793 ms/op

Iteration   3: 4.062 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.159 ms/op
                 listUser·p0.50:   3.977 ms/op
                 listUser·p0.90:   4.358 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.119 ms/op
                 listUser·p0.999:  15.371 ms/op
                 listUser·p0.9999: 18.034 ms/op
                 listUser·p1.00:   18.350 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238747
  mean =      4.019 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 22 
    [ 2.500,  5.000) = 230629 
    [ 5.000,  7.500) = 5962 
    [ 7.500, 10.000) = 1377 
    [10.000, 12.500) = 278 
    [12.500, 15.000) = 199 
    [15.000, 17.500) = 158 
    [17.500, 20.000) = 62 
    [20.000, 22.500) = 40 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.919 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.375 ms/op
     p(95.0000) =      4.628 ms/op
     p(99.0000) =      7.274 ms/op
     p(99.9000) =     15.483 ms/op
     p(99.9900) =     22.381 ms/op
     p(99.9990) =     23.628 ms/op
     p(99.9999) =     24.084 ms/op
    p(100.0000) =     24.084 ms/op


# Run complete. Total time: 00:13:13

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.457 ± 0.385  ops/ms
ClientPb.existUser                       thrpt       3   9.852 ± 6.017  ops/ms
ClientPb.getUser                         thrpt       3   9.344 ± 4.364  ops/ms
ClientPb.listUser                        thrpt       3   8.100 ± 5.187  ops/ms
ClientPb.createUser                       avgt       3   3.393 ± 0.611   ms/op
ClientPb.existUser                        avgt       3   3.249 ± 0.303   ms/op
ClientPb.getUser                          avgt       3   3.357 ± 0.884   ms/op
ClientPb.listUser                         avgt       3   3.898 ± 1.701   ms/op
ClientPb.createUser                     sample  278650   3.445 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.844           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.260           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.981           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.309           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.013           ms/op
ClientPb.createUser:createUser·p0.999   sample          14.336           ms/op
ClientPb.createUser:createUser·p0.9999  sample          26.678           ms/op
ClientPb.createUser:createUser·p1.00    sample          29.131           ms/op
ClientPb.existUser                      sample  289464   3.318 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.180           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.265           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.998           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.861           ms/op
ClientPb.existUser:existUser·p0.9999    sample          26.182           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.786           ms/op
ClientPb.getUser                        sample  270892   3.543 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.746           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.412           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.030           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.669           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.463           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.973           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.639           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.999           ms/op
ClientPb.listUser                       sample  238747   4.019 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.919           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.875           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.375           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.628           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.274           ms/op
ClientPb.listUser:listUser·p0.999       sample          15.483           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.381           ms/op
ClientPb.listUser:listUser·p1.00        sample          24.084           ms/op
