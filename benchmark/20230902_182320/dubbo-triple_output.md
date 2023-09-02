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
# Warmup Iteration   1: 1.683 ops/ms
# Warmup Iteration   2: 3.384 ops/ms
# Warmup Iteration   3: 6.948 ops/ms
Iteration   1: 7.408 ops/ms
Iteration   2: 7.546 ops/ms
Iteration   3: 7.651 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.535 ±(99.9%) 2.227 ops/ms [Average]
  (min, avg, max) = (7.408, 7.535, 7.651), stdev = 0.122
  CI (99.9%): [5.308, 9.762] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.303 ops/ms
# Warmup Iteration   2: 6.563 ops/ms
# Warmup Iteration   3: 7.717 ops/ms
Iteration   1: 8.093 ops/ms
Iteration   2: 8.174 ops/ms
Iteration   3: 8.070 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.113 ±(99.9%) 1.000 ops/ms [Average]
  (min, avg, max) = (8.070, 8.113, 8.174), stdev = 0.055
  CI (99.9%): [7.113, 9.112] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 2.126 ops/ms
# Warmup Iteration   2: 5.777 ops/ms
# Warmup Iteration   3: 7.593 ops/ms
Iteration   1: 7.482 ops/ms
Iteration   2: 7.629 ops/ms
Iteration   3: 7.596 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.569 ±(99.9%) 1.400 ops/ms [Average]
  (min, avg, max) = (7.482, 7.569, 7.629), stdev = 0.077
  CI (99.9%): [6.169, 8.969] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.010 ops/ms
# Warmup Iteration   2: 5.296 ops/ms
# Warmup Iteration   3: 6.694 ops/ms
Iteration   1: 6.668 ops/ms
Iteration   2: 6.836 ops/ms
Iteration   3: 6.528 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.677 ±(99.9%) 2.816 ops/ms [Average]
  (min, avg, max) = (6.528, 6.677, 6.836), stdev = 0.154
  CI (99.9%): [3.862, 9.493] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 13.392 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 4.662 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.374 ±(99.9%) 0.007 ms/op
Iteration   1: 4.096 ±(99.9%) 0.010 ms/op
Iteration   2: 4.049 ±(99.9%) 0.005 ms/op
Iteration   3: 4.014 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.053 ±(99.9%) 0.748 ms/op [Average]
  (min, avg, max) = (4.014, 4.053, 4.096), stdev = 0.041
  CI (99.9%): [3.305, 4.801] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:41
# Fork: 1 of 1
# Warmup Iteration   1: 11.898 ±(99.9%) 0.052 ms/op
# Warmup Iteration   2: 4.425 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.185 ±(99.9%) 0.007 ms/op
Iteration   1: 3.997 ±(99.9%) 0.008 ms/op
Iteration   2: 3.760 ±(99.9%) 0.008 ms/op
Iteration   3: 3.813 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.857 ±(99.9%) 2.273 ms/op [Average]
  (min, avg, max) = (3.760, 3.857, 3.997), stdev = 0.125
  CI (99.9%): [1.584, 6.129] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 12.479 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.675 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.246 ±(99.9%) 0.007 ms/op
Iteration   1: 4.246 ±(99.9%) 0.006 ms/op
Iteration   2: 4.262 ±(99.9%) 0.007 ms/op
Iteration   3: 4.108 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.205 ±(99.9%) 1.542 ms/op [Average]
  (min, avg, max) = (4.108, 4.205, 4.262), stdev = 0.085
  CI (99.9%): [2.663, 5.747] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:29
# Fork: 1 of 1
# Warmup Iteration   1: 15.335 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 5.794 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.803 ±(99.9%) 0.011 ms/op
Iteration   1: 4.801 ±(99.9%) 0.012 ms/op
Iteration   2: 4.707 ±(99.9%) 0.010 ms/op
Iteration   3: 4.635 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.714 ±(99.9%) 1.511 ms/op [Average]
  (min, avg, max) = (4.635, 4.714, 4.801), stdev = 0.083
  CI (99.9%): [3.203, 6.226] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 12.735 ±(99.9%) 0.166 ms/op
# Warmup Iteration   2: 5.138 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 4.414 ±(99.9%) 0.018 ms/op
Iteration   1: 4.267 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.399 ms/op
                 createUser·p0.50:   3.924 ms/op
                 createUser·p0.90:   5.489 ms/op
                 createUser·p0.95:   6.308 ms/op
                 createUser·p0.99:   8.700 ms/op
                 createUser·p0.999:  21.725 ms/op
                 createUser·p0.9999: 24.790 ms/op
                 createUser·p1.00:   27.394 ms/op

Iteration   2: 3.892 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.718 ms/op
                 createUser·p0.50:   3.727 ms/op
                 createUser·p0.90:   4.424 ms/op
                 createUser·p0.95:   4.899 ms/op
                 createUser·p0.99:   6.955 ms/op
                 createUser·p0.999:  12.337 ms/op
                 createUser·p0.9999: 24.765 ms/op
                 createUser·p1.00:   26.542 ms/op

Iteration   3: 4.029 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.901 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.669 ms/op
                 createUser·p0.95:   5.104 ms/op
                 createUser·p0.99:   7.360 ms/op
                 createUser·p0.999:  26.903 ms/op
                 createUser·p0.9999: 34.144 ms/op
                 createUser·p1.00:   35.783 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236554
  mean =      4.057 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 416 
    [ 2.500,  5.000) = 217458 
    [ 5.000,  7.500) = 15566 
    [ 7.500, 10.000) = 2209 
    [10.000, 12.500) = 520 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 10 
    [30.000, 32.500) = 16 
    [32.500, 35.000) = 30 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.399 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.809 ms/op
     p(95.0000) =      5.652 ms/op
     p(99.0000) =      8.102 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     33.282 ms/op
     p(99.9990) =     34.680 ms/op
     p(99.9999) =     35.783 ms/op
    p(100.0000) =     35.783 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 12.196 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 4.458 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 4.053 ±(99.9%) 0.014 ms/op
Iteration   1: 3.945 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.630 ms/op
                 existUser·p0.50:   3.703 ms/op
                 existUser·p0.90:   4.407 ms/op
                 existUser·p0.95:   5.780 ms/op
                 existUser·p0.99:   8.421 ms/op
                 existUser·p0.999:  17.316 ms/op
                 existUser·p0.9999: 26.113 ms/op
                 existUser·p1.00:   27.591 ms/op

Iteration   2: 3.906 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.637 ms/op
                 existUser·p0.95:   5.169 ms/op
                 existUser·p0.99:   7.206 ms/op
                 existUser·p0.999:  15.258 ms/op
                 existUser·p0.9999: 26.536 ms/op
                 existUser·p1.00:   27.263 ms/op

Iteration   3: 3.803 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.827 ms/op
                 existUser·p0.50:   3.707 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.448 ms/op
                 existUser·p0.99:   6.865 ms/op
                 existUser·p0.999:  13.566 ms/op
                 existUser·p0.9999: 37.525 ms/op
                 existUser·p1.00:   38.011 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247165
  mean =      3.883 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 449 
    [ 2.500,  5.000) = 233380 
    [ 5.000,  7.500) = 10067 
    [ 7.500, 10.000) = 2316 
    [10.000, 12.500) = 586 
    [12.500, 15.000) = 119 
    [15.000, 17.500) = 42 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 59 
    [27.500, 30.000) = 8 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 24 

  Percentiles, ms/op:
      p(0.0000) =      1.505 ms/op
     p(50.0000) =      3.703 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      5.104 ms/op
     p(99.0000) =      8.126 ms/op
     p(99.9000) =     15.215 ms/op
     p(99.9900) =     35.922 ms/op
     p(99.9990) =     37.980 ms/op
     p(99.9999) =     38.011 ms/op
    p(100.0000) =     38.011 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.365 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.607 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.014 ms/op
Iteration   1: 4.097 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.477 ms/op
                 getUser·p0.50:   3.838 ms/op
                 getUser·p0.90:   4.948 ms/op
                 getUser·p0.95:   5.538 ms/op
                 getUser·p0.99:   8.136 ms/op
                 getUser·p0.999:  23.817 ms/op
                 getUser·p0.9999: 27.990 ms/op
                 getUser·p1.00:   29.655 ms/op

Iteration   2: 4.037 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.823 ms/op
                 getUser·p0.50:   3.863 ms/op
                 getUser·p0.90:   4.530 ms/op
                 getUser·p0.95:   5.734 ms/op
                 getUser·p0.99:   7.455 ms/op
                 getUser·p0.999:  12.845 ms/op
                 getUser·p0.9999: 31.326 ms/op
                 getUser·p1.00:   32.768 ms/op

Iteration   3: 3.956 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.741 ms/op
                 getUser·p0.50:   3.772 ms/op
                 getUser·p0.90:   4.415 ms/op
                 getUser·p0.95:   5.104 ms/op
                 getUser·p0.99:   7.438 ms/op
                 getUser·p0.999:  28.380 ms/op
                 getUser·p0.9999: 32.637 ms/op
                 getUser·p1.00:   34.603 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238287
  mean =      4.029 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 320 
    [ 2.500,  5.000) = 220882 
    [ 5.000,  7.500) = 14459 
    [ 7.500, 10.000) = 1588 
    [10.000, 12.500) = 566 
    [12.500, 15.000) = 147 
    [15.000, 17.500) = 34 
    [17.500, 20.000) = 3 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 49 
    [27.500, 30.000) = 93 
    [30.000, 32.500) = 58 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.477 ms/op
     p(50.0000) =      3.822 ms/op
     p(90.0000) =      4.694 ms/op
     p(95.0000) =      5.448 ms/op
     p(99.0000) =      7.766 ms/op
     p(99.9000) =     23.803 ms/op
     p(99.9900) =     32.145 ms/op
     p(99.9990) =     33.856 ms/op
     p(99.9999) =     34.603 ms/op
    p(100.0000) =     34.603 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 13.629 ±(99.9%) 0.200 ms/op
# Warmup Iteration   2: 5.539 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.968 ±(99.9%) 0.022 ms/op
Iteration   1: 4.711 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.030 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.145 ms/op
                 listUser·p0.95:   5.964 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  24.052 ms/op
                 listUser·p0.9999: 26.271 ms/op
                 listUser·p1.00:   27.361 ms/op

Iteration   2: 4.810 ±(99.9%) 0.015 ms/op
                 listUser·p0.00:   1.991 ms/op
                 listUser·p0.50:   4.596 ms/op
                 listUser·p0.90:   5.284 ms/op
                 listUser·p0.95:   6.701 ms/op
                 listUser·p0.99:   9.454 ms/op
                 listUser·p0.999:  19.843 ms/op
                 listUser·p0.9999: 27.373 ms/op
                 listUser·p1.00:   28.246 ms/op

Iteration   3: 4.739 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.815 ms/op
                 listUser·p0.50:   4.489 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   6.160 ms/op
                 listUser·p0.99:   9.489 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 21.227 ms/op
                 listUser·p1.00:   23.921 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 201756
  mean =      4.753 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 15 
    [ 2.500,  5.000) = 165721 
    [ 5.000,  7.500) = 29713 
    [ 7.500, 10.000) = 4784 
    [10.000, 12.500) = 986 
    [12.500, 15.000) = 149 
    [15.000, 17.500) = 74 
    [17.500, 20.000) = 113 
    [20.000, 22.500) = 70 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 62 

  Percentiles, ms/op:
      p(0.0000) =      1.815 ms/op
     p(50.0000) =      4.522 ms/op
     p(90.0000) =      5.292 ms/op
     p(95.0000) =      6.226 ms/op
     p(99.0000) =      9.568 ms/op
     p(99.9000) =     19.996 ms/op
     p(99.9900) =     26.376 ms/op
     p(99.9990) =     28.179 ms/op
     p(99.9999) =     28.246 ms/op
    p(100.0000) =     28.246 ms/op


# Run complete. Total time: 00:13:15

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.535 ± 2.227  ops/ms
ClientPb.existUser                       thrpt       3   8.113 ± 1.000  ops/ms
ClientPb.getUser                         thrpt       3   7.569 ± 1.400  ops/ms
ClientPb.listUser                        thrpt       3   6.677 ± 2.816  ops/ms
ClientPb.createUser                       avgt       3   4.053 ± 0.748   ms/op
ClientPb.existUser                        avgt       3   3.857 ± 2.273   ms/op
ClientPb.getUser                          avgt       3   4.205 ± 1.542   ms/op
ClientPb.listUser                         avgt       3   4.714 ± 1.511   ms/op
ClientPb.createUser                     sample  236554   4.057 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.399           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.809           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.652           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.479           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.282           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.783           ms/op
ClientPb.existUser                      sample  247165   3.883 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.505           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.104           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.126           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.215           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.922           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.011           ms/op
ClientPb.getUser                        sample  238287   4.029 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.477           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.822           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.694           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.448           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.766           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.803           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.145           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.603           ms/op
ClientPb.listUser                       sample  201756   4.753 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.815           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.292           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.226           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.568           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.996           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.376           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.246           ms/op
