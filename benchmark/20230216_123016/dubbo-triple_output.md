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
# Warmup Iteration   1: 1.911 ops/ms
# Warmup Iteration   2: 4.568 ops/ms
# Warmup Iteration   3: 8.389 ops/ms
Iteration   1: 8.770 ops/ms
Iteration   2: 8.856 ops/ms
Iteration   3: 9.428 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.018 ±(99.9%) 6.526 ops/ms [Average]
  (min, avg, max) = (8.770, 9.018, 9.428), stdev = 0.358
  CI (99.9%): [2.492, 15.545] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 2.537 ops/ms
# Warmup Iteration   2: 8.653 ops/ms
# Warmup Iteration   3: 9.566 ops/ms
Iteration   1: 10.024 ops/ms
Iteration   2: 9.962 ops/ms
Iteration   3: 9.599 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.862 ±(99.9%) 4.184 ops/ms [Average]
  (min, avg, max) = (9.599, 9.862, 10.024), stdev = 0.229
  CI (99.9%): [5.678, 14.045] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:57
# Fork: 1 of 1
# Warmup Iteration   1: 2.689 ops/ms
# Warmup Iteration   2: 7.869 ops/ms
# Warmup Iteration   3: 9.237 ops/ms
Iteration   1: 9.260 ops/ms
Iteration   2: 9.436 ops/ms
Iteration   3: 9.515 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.404 ±(99.9%) 2.379 ops/ms [Average]
  (min, avg, max) = (9.260, 9.404, 9.515), stdev = 0.130
  CI (99.9%): [7.025, 11.783] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.596 ops/ms
# Warmup Iteration   2: 6.793 ops/ms
# Warmup Iteration   3: 7.795 ops/ms
Iteration   1: 7.801 ops/ms
Iteration   2: 7.941 ops/ms
Iteration   3: 8.105 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  7.949 ±(99.9%) 2.779 ops/ms [Average]
  (min, avg, max) = (7.801, 7.949, 8.105), stdev = 0.152
  CI (99.9%): [5.170, 10.728] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 10.288 ±(99.9%) 0.039 ms/op
# Warmup Iteration   2: 3.959 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.559 ±(99.9%) 0.008 ms/op
Iteration   1: 3.468 ±(99.9%) 0.009 ms/op
Iteration   2: 3.431 ±(99.9%) 0.004 ms/op
Iteration   3: 3.279 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.393 ±(99.9%) 1.831 ms/op [Average]
  (min, avg, max) = (3.279, 3.393, 3.468), stdev = 0.100
  CI (99.9%): [1.562, 5.223] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 8.228 ±(99.9%) 0.025 ms/op
# Warmup Iteration   2: 3.553 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.274 ±(99.9%) 0.004 ms/op
Iteration   1: 3.347 ±(99.9%) 0.007 ms/op
Iteration   2: 3.263 ±(99.9%) 0.004 ms/op
Iteration   3: 3.377 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.329 ±(99.9%) 1.079 ms/op [Average]
  (min, avg, max) = (3.263, 3.329, 3.377), stdev = 0.059
  CI (99.9%): [2.249, 4.408] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 9.384 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.961 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.637 ±(99.9%) 0.002 ms/op
Iteration   1: 3.475 ±(99.9%) 0.010 ms/op
Iteration   2: 3.349 ±(99.9%) 0.013 ms/op
Iteration   3: 3.561 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.462 ±(99.9%) 1.943 ms/op [Average]
  (min, avg, max) = (3.349, 3.462, 3.561), stdev = 0.107
  CI (99.9%): [1.518, 5.405] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 10.536 ±(99.9%) 0.032 ms/op
# Warmup Iteration   2: 4.448 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.127 ±(99.9%) 0.010 ms/op
Iteration   1: 3.997 ±(99.9%) 0.011 ms/op
Iteration   2: 4.076 ±(99.9%) 0.012 ms/op
Iteration   3: 4.259 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.111 ±(99.9%) 2.446 ms/op [Average]
  (min, avg, max) = (3.997, 4.111, 4.259), stdev = 0.134
  CI (99.9%): [1.664, 6.557] (assumes normal distribution)


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
# Warmup Iteration   1: 9.710 ±(99.9%) 0.123 ms/op
# Warmup Iteration   2: 4.125 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.506 ±(99.9%) 0.011 ms/op
Iteration   1: 3.406 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.581 ms/op
                 createUser·p0.50:   3.215 ms/op
                 createUser·p0.90:   3.879 ms/op
                 createUser·p0.95:   4.325 ms/op
                 createUser·p0.99:   6.095 ms/op
                 createUser·p0.999:  21.496 ms/op
                 createUser·p0.9999: 23.613 ms/op
                 createUser·p1.00:   25.297 ms/op

Iteration   2: 3.497 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.722 ms/op
                 createUser·p0.50:   3.326 ms/op
                 createUser·p0.90:   4.010 ms/op
                 createUser·p0.95:   4.776 ms/op
                 createUser·p0.99:   6.128 ms/op
                 createUser·p0.999:  24.037 ms/op
                 createUser·p0.9999: 31.939 ms/op
                 createUser·p1.00:   34.013 ms/op

Iteration   3: 3.436 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.686 ms/op
                 createUser·p0.50:   3.297 ms/op
                 createUser·p0.90:   3.908 ms/op
                 createUser·p0.95:   4.284 ms/op
                 createUser·p0.99:   5.644 ms/op
                 createUser·p0.999:  21.529 ms/op
                 createUser·p0.9999: 28.435 ms/op
                 createUser·p1.00:   29.098 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 278586
  mean =      3.446 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4710 
    [ 2.500,  5.000) = 265396 
    [ 5.000,  7.500) = 7429 
    [ 7.500, 10.000) = 581 
    [10.000, 12.500) = 129 
    [12.500, 15.000) = 53 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 56 
    [22.500, 25.000) = 118 
    [25.000, 27.500) = 65 
    [27.500, 30.000) = 17 
    [30.000, 32.500) = 28 
    [32.500, 35.000) = 4 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.581 ms/op
     p(50.0000) =      3.273 ms/op
     p(90.0000) =      3.928 ms/op
     p(95.0000) =      4.407 ms/op
     p(99.0000) =      5.956 ms/op
     p(99.9000) =     21.542 ms/op
     p(99.9900) =     30.942 ms/op
     p(99.9990) =     33.522 ms/op
     p(99.9999) =     34.013 ms/op
    p(100.0000) =     34.013 ms/op


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
# Warmup Iteration   1: 8.567 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 3.754 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.263 ±(99.9%) 0.008 ms/op
Iteration   1: 3.218 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.391 ms/op
                 existUser·p0.50:   3.125 ms/op
                 existUser·p0.90:   3.514 ms/op
                 existUser·p0.95:   3.719 ms/op
                 existUser·p0.99:   5.456 ms/op
                 existUser·p0.999:  10.537 ms/op
                 existUser·p0.9999: 21.465 ms/op
                 existUser·p1.00:   22.872 ms/op

Iteration   2: 3.281 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.174 ms/op
                 existUser·p0.90:   3.584 ms/op
                 existUser·p0.95:   3.817 ms/op
                 existUser·p0.99:   5.997 ms/op
                 existUser·p0.999:  11.387 ms/op
                 existUser·p0.9999: 26.968 ms/op
                 existUser·p1.00:   28.672 ms/op

Iteration   3: 3.306 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.726 ms/op
                 existUser·p0.50:   3.158 ms/op
                 existUser·p0.90:   3.674 ms/op
                 existUser·p0.95:   3.961 ms/op
                 existUser·p0.99:   5.743 ms/op
                 existUser·p0.999:  15.661 ms/op
                 existUser·p0.9999: 28.279 ms/op
                 existUser·p1.00:   29.884 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 293574
  mean =      3.268 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4785 
    [ 2.500,  5.000) = 283725 
    [ 5.000,  7.500) = 4147 
    [ 7.500, 10.000) = 486 
    [10.000, 12.500) = 119 
    [12.500, 15.000) = 24 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 23 
    [20.000, 22.500) = 115 
    [22.500, 25.000) = 71 
    [25.000, 27.500) = 64 

  Percentiles, ms/op:
      p(0.0000) =      1.391 ms/op
     p(50.0000) =      3.150 ms/op
     p(90.0000) =      3.598 ms/op
     p(95.0000) =      3.826 ms/op
     p(99.0000) =      5.726 ms/op
     p(99.9000) =     12.901 ms/op
     p(99.9900) =     27.097 ms/op
     p(99.9990) =     29.022 ms/op
     p(99.9999) =     29.884 ms/op
    p(100.0000) =     29.884 ms/op


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
# Warmup Iteration   1: 10.585 ±(99.9%) 0.144 ms/op
# Warmup Iteration   2: 4.061 ±(99.9%) 0.018 ms/op
# Warmup Iteration   3: 3.600 ±(99.9%) 0.011 ms/op
Iteration   1: 3.439 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.200 ms/op
                 getUser·p0.50:   3.265 ms/op
                 getUser·p0.90:   3.793 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  22.102 ms/op
                 getUser·p0.9999: 27.790 ms/op
                 getUser·p1.00:   28.246 ms/op

Iteration   2: 3.551 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.400 ms/op
                 getUser·p0.90:   4.133 ms/op
                 getUser·p0.95:   4.604 ms/op
                 getUser·p0.99:   6.201 ms/op
                 getUser·p0.999:  23.492 ms/op
                 getUser·p0.9999: 25.526 ms/op
                 getUser·p1.00:   26.837 ms/op

Iteration   3: 3.541 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.268 ms/op
                 getUser·p0.50:   3.412 ms/op
                 getUser·p0.90:   4.104 ms/op
                 getUser·p0.95:   4.383 ms/op
                 getUser·p0.99:   6.210 ms/op
                 getUser·p0.999:  22.892 ms/op
                 getUser·p0.9999: 32.570 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 273629
  mean =      3.510 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8709 
    [ 2.500,  5.000) = 256308 
    [ 5.000,  7.500) = 7382 
    [ 7.500, 10.000) = 766 
    [10.000, 12.500) = 126 
    [12.500, 15.000) = 38 
    [15.000, 17.500) = 12 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 158 
    [25.000, 27.500) = 70 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 22 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.200 ms/op
     p(50.0000) =      3.363 ms/op
     p(90.0000) =      4.055 ms/op
     p(95.0000) =      4.473 ms/op
     p(99.0000) =      6.382 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     31.162 ms/op
     p(99.9990) =     33.220 ms/op
     p(99.9999) =     33.751 ms/op
    p(100.0000) =     33.751 ms/op


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
# Warmup Iteration   1: 12.007 ±(99.9%) 0.161 ms/op
# Warmup Iteration   2: 4.553 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.197 ±(99.9%) 0.014 ms/op
Iteration   1: 4.102 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.485 ms/op
                 listUser·p0.50:   3.981 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   7.520 ms/op
                 listUser·p0.999:  22.053 ms/op
                 listUser·p0.9999: 26.661 ms/op
                 listUser·p1.00:   27.001 ms/op

Iteration   2: 4.091 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.038 ms/op
                 listUser·p0.50:   4.002 ms/op
                 listUser·p0.90:   4.391 ms/op
                 listUser·p0.95:   4.604 ms/op
                 listUser·p0.99:   7.365 ms/op
                 listUser·p0.999:  16.464 ms/op
                 listUser·p0.9999: 18.121 ms/op
                 listUser·p1.00:   21.168 ms/op

Iteration   3: 4.105 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.040 ms/op
                 listUser·p0.50:   3.924 ms/op
                 listUser·p0.90:   4.768 ms/op
                 listUser·p0.95:   5.038 ms/op
                 listUser·p0.99:   6.816 ms/op
                 listUser·p0.999:  14.751 ms/op
                 listUser·p0.9999: 17.793 ms/op
                 listUser·p1.00:   18.973 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 233991
  mean =      4.099 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 61 
    [ 2.500,  5.000) = 224675 
    [ 5.000,  7.500) = 7188 
    [ 7.500, 10.000) = 1261 
    [10.000, 12.500) = 224 
    [12.500, 15.000) = 181 
    [15.000, 17.500) = 216 
    [17.500, 20.000) = 52 
    [20.000, 22.500) = 61 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 40 

  Percentiles, ms/op:
      p(0.0000) =      1.485 ms/op
     p(50.0000) =      3.973 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      4.866 ms/op
     p(99.0000) =      7.291 ms/op
     p(99.9000) =     16.777 ms/op
     p(99.9900) =     25.939 ms/op
     p(99.9990) =     26.935 ms/op
     p(99.9999) =     27.001 ms/op
    p(100.0000) =     27.001 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.018 ± 6.526  ops/ms
ClientPb.existUser                       thrpt       3   9.862 ± 4.184  ops/ms
ClientPb.getUser                         thrpt       3   9.404 ± 2.379  ops/ms
ClientPb.listUser                        thrpt       3   7.949 ± 2.779  ops/ms
ClientPb.createUser                       avgt       3   3.393 ± 1.831   ms/op
ClientPb.existUser                        avgt       3   3.329 ± 1.079   ms/op
ClientPb.getUser                          avgt       3   3.462 ± 1.943   ms/op
ClientPb.listUser                         avgt       3   4.111 ± 2.446   ms/op
ClientPb.createUser                     sample  278586   3.446 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.581           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.273           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.928           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.956           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.542           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.942           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.013           ms/op
ClientPb.existUser                      sample  293574   3.268 ± 0.005   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.391           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.150           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.598           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.826           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.726           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.901           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.097           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.884           ms/op
ClientPb.getUser                        sample  273629   3.510 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.200           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.363           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.055           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.473           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.382           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.479           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.162           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.751           ms/op
ClientPb.listUser                       sample  233991   4.099 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.485           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.973           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.497           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.866           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.291           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.777           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.939           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.001           ms/op
