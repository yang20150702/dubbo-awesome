# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 2.685 ops/ms
# Warmup Iteration   2: 6.150 ops/ms
# Warmup Iteration   3: 9.219 ops/ms
Iteration   1: 10.041 ops/ms
Iteration   2: 9.574 ops/ms
Iteration   3: 10.180 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.931 ±(99.9%) 5.794 ops/ms [Average]
  (min, avg, max) = (9.574, 9.931, 10.180), stdev = 0.318
  CI (99.9%): [4.138, 15.725] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 3.221 ops/ms
# Warmup Iteration   2: 9.325 ops/ms
# Warmup Iteration   3: 10.540 ops/ms
Iteration   1: 10.226 ops/ms
Iteration   2: 10.105 ops/ms
Iteration   3: 9.726 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.019 ±(99.9%) 4.763 ops/ms [Average]
  (min, avg, max) = (9.726, 10.019, 10.226), stdev = 0.261
  CI (99.9%): [5.256, 14.782] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:00
# Fork: 1 of 1
# Warmup Iteration   1: 4.126 ops/ms
# Warmup Iteration   2: 9.159 ops/ms
# Warmup Iteration   3: 9.796 ops/ms
Iteration   1: 10.059 ops/ms
Iteration   2: 10.274 ops/ms
Iteration   3: 9.733 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.022 ±(99.9%) 4.963 ops/ms [Average]
  (min, avg, max) = (9.733, 10.022, 10.274), stdev = 0.272
  CI (99.9%): [5.059, 14.985] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 3.273 ops/ms
# Warmup Iteration   2: 8.008 ops/ms
# Warmup Iteration   3: 8.510 ops/ms
Iteration   1: 8.432 ops/ms
Iteration   2: 8.769 ops/ms
Iteration   3: 8.565 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.588 ±(99.9%) 3.093 ops/ms [Average]
  (min, avg, max) = (8.432, 8.588, 8.769), stdev = 0.170
  CI (99.9%): [5.495, 11.682] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:47
# Fork: 1 of 1
# Warmup Iteration   1: 8.034 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.743 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.310 ±(99.9%) 0.007 ms/op
Iteration   1: 3.188 ±(99.9%) 0.003 ms/op
Iteration   2: 3.178 ±(99.9%) 0.007 ms/op
Iteration   3: 3.232 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.199 ±(99.9%) 0.531 ms/op [Average]
  (min, avg, max) = (3.178, 3.199, 3.232), stdev = 0.029
  CI (99.9%): [2.669, 3.730] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.992 ±(99.9%) 0.020 ms/op
# Warmup Iteration   2: 3.391 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.067 ±(99.9%) 0.002 ms/op
Iteration   1: 3.041 ±(99.9%) 0.005 ms/op
Iteration   2: 3.037 ±(99.9%) 0.004 ms/op
Iteration   3: 3.011 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.030 ±(99.9%) 0.303 ms/op [Average]
  (min, avg, max) = (3.011, 3.030, 3.041), stdev = 0.017
  CI (99.9%): [2.727, 3.332] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:36
# Fork: 1 of 1
# Warmup Iteration   1: 7.564 ±(99.9%) 0.019 ms/op
# Warmup Iteration   2: 3.360 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.422 ±(99.9%) 0.005 ms/op
Iteration   1: 3.227 ±(99.9%) 0.003 ms/op
Iteration   2: 3.180 ±(99.9%) 0.008 ms/op
Iteration   3: 3.186 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.198 ±(99.9%) 0.473 ms/op [Average]
  (min, avg, max) = (3.180, 3.198, 3.227), stdev = 0.026
  CI (99.9%): [2.724, 3.671] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 9.886 ±(99.9%) 0.031 ms/op
# Warmup Iteration   2: 4.014 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.808 ±(99.9%) 0.006 ms/op
Iteration   1: 3.731 ±(99.9%) 0.010 ms/op
Iteration   2: 3.782 ±(99.9%) 0.009 ms/op
Iteration   3: 3.756 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.756 ±(99.9%) 0.458 ms/op [Average]
  (min, avg, max) = (3.731, 3.756, 3.782), stdev = 0.025
  CI (99.9%): [3.299, 4.214] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 7.872 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.588 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.272 ±(99.9%) 0.009 ms/op
Iteration   1: 3.279 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   0.892 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.826 ms/op
                 createUser·p0.95:   4.399 ms/op
                 createUser·p0.99:   5.628 ms/op
                 createUser·p0.999:  10.535 ms/op
                 createUser·p0.9999: 20.783 ms/op
                 createUser·p1.00:   21.463 ms/op

Iteration   2: 3.171 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.305 ms/op
                 createUser·p0.50:   3.129 ms/op
                 createUser·p0.90:   3.482 ms/op
                 createUser·p0.95:   3.781 ms/op
                 createUser·p0.99:   5.431 ms/op
                 createUser·p0.999:  9.519 ms/op
                 createUser·p0.9999: 23.003 ms/op
                 createUser·p1.00:   23.626 ms/op

Iteration   3: 3.266 ±(99.9%) 0.008 ms/op
                 createUser·p0.00:   1.180 ms/op
                 createUser·p0.50:   3.203 ms/op
                 createUser·p0.90:   3.748 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.530 ms/op
                 createUser·p0.999:  15.566 ms/op
                 createUser·p0.9999: 19.700 ms/op
                 createUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 296392
  mean =      3.238 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19389 
    [ 2.500,  5.000) = 269399 
    [ 5.000,  7.500) = 6641 
    [ 7.500, 10.000) = 542 
    [10.000, 12.500) = 68 
    [12.500, 15.000) = 36 
    [15.000, 17.500) = 81 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 100 
    [22.500, 25.000) = 17 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.892 ms/op
     p(50.0000) =      3.166 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.071 ms/op
     p(99.0000) =      5.521 ms/op
     p(99.9000) =     15.427 ms/op
     p(99.9900) =     22.097 ms/op
     p(99.9990) =     23.594 ms/op
     p(99.9999) =     23.626 ms/op
    p(100.0000) =     23.626 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 7.600 ±(99.9%) 0.084 ms/op
# Warmup Iteration   2: 3.355 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.048 ±(99.9%) 0.007 ms/op
Iteration   1: 3.145 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.399 ms/op
                 existUser·p0.50:   3.035 ms/op
                 existUser·p0.90:   3.424 ms/op
                 existUser·p0.95:   4.108 ms/op
                 existUser·p0.99:   6.077 ms/op
                 existUser·p0.999:  9.507 ms/op
                 existUser·p0.9999: 22.543 ms/op
                 existUser·p1.00:   23.298 ms/op

Iteration   2: 3.141 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.048 ms/op
                 existUser·p0.50:   3.076 ms/op
                 existUser·p0.90:   3.494 ms/op
                 existUser·p0.95:   3.789 ms/op
                 existUser·p0.99:   5.497 ms/op
                 existUser·p0.999:  11.095 ms/op
                 existUser·p0.9999: 22.926 ms/op
                 existUser·p1.00:   23.658 ms/op

Iteration   3: 3.056 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.669 ms/op
                 existUser·p0.50:   3.039 ms/op
                 existUser·p0.90:   3.191 ms/op
                 existUser·p0.95:   3.518 ms/op
                 existUser·p0.99:   5.251 ms/op
                 existUser·p0.999:  8.167 ms/op
                 existUser·p0.9999: 21.103 ms/op
                 existUser·p1.00:   21.627 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 308208
  mean =      3.113 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 19400 
    [ 2.500,  5.000) = 282312 
    [ 5.000,  7.500) = 5676 
    [ 7.500, 10.000) = 397 
    [10.000, 12.500) = 131 
    [12.500, 15.000) = 3 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 123 
    [22.500, 25.000) = 29 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.048 ms/op
     p(50.0000) =      3.047 ms/op
     p(90.0000) =      3.391 ms/op
     p(95.0000) =      3.764 ms/op
     p(99.0000) =      5.628 ms/op
     p(99.9000) =     10.977 ms/op
     p(99.9900) =     22.392 ms/op
     p(99.9990) =     23.295 ms/op
     p(99.9999) =     23.658 ms/op
    p(100.0000) =     23.658 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 6.575 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 3.375 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.206 ±(99.9%) 0.010 ms/op
Iteration   1: 3.278 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.262 ms/op
                 getUser·p0.50:   3.211 ms/op
                 getUser·p0.90:   3.875 ms/op
                 getUser·p0.95:   4.268 ms/op
                 getUser·p0.99:   5.751 ms/op
                 getUser·p0.999:  17.629 ms/op
                 getUser·p0.9999: 20.102 ms/op
                 getUser·p1.00:   21.987 ms/op

Iteration   2: 3.231 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.098 ms/op
                 getUser·p0.50:   3.183 ms/op
                 getUser·p0.90:   3.682 ms/op
                 getUser·p0.95:   4.178 ms/op
                 getUser·p0.99:   5.685 ms/op
                 getUser·p0.999:  8.961 ms/op
                 getUser·p0.9999: 21.904 ms/op
                 getUser·p1.00:   22.577 ms/op

Iteration   3: 3.258 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.118 ms/op
                 getUser·p0.50:   3.138 ms/op
                 getUser·p0.90:   3.690 ms/op
                 getUser·p0.95:   4.637 ms/op
                 getUser·p0.99:   6.119 ms/op
                 getUser·p0.999:  9.870 ms/op
                 getUser·p0.9999: 18.848 ms/op
                 getUser·p1.00:   19.399 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 294774
  mean =      3.256 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27633 
    [ 2.500,  5.000) = 258650 
    [ 5.000,  7.500) = 7733 
    [ 7.500, 10.000) = 376 
    [10.000, 12.500) = 77 
    [12.500, 15.000) = 33 
    [15.000, 17.500) = 47 
    [17.500, 20.000) = 144 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 2 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.098 ms/op
     p(50.0000) =      3.183 ms/op
     p(90.0000) =      3.772 ms/op
     p(95.0000) =      4.325 ms/op
     p(99.0000) =      5.743 ms/op
     p(99.9000) =     13.138 ms/op
     p(99.9900) =     21.135 ms/op
     p(99.9990) =     22.296 ms/op
     p(99.9999) =     22.577 ms/op
    p(100.0000) =     22.577 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_352, OpenJDK 64-Bit Server VM, 25.352-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.352-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 8.811 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 4.032 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 3.845 ±(99.9%) 0.012 ms/op
Iteration   1: 3.746 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.368 ms/op
                 listUser·p0.50:   3.629 ms/op
                 listUser·p0.90:   4.043 ms/op
                 listUser·p0.95:   4.358 ms/op
                 listUser·p0.99:   7.041 ms/op
                 listUser·p0.999:  17.039 ms/op
                 listUser·p0.9999: 20.717 ms/op
                 listUser·p1.00:   22.151 ms/op

Iteration   2: 3.704 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.961 ms/op
                 listUser·p0.95:   4.243 ms/op
                 listUser·p0.99:   7.105 ms/op
                 listUser·p0.999:  14.057 ms/op
                 listUser·p0.9999: 17.236 ms/op
                 listUser·p1.00:   17.269 ms/op

Iteration   3: 3.795 ±(99.9%) 0.008 ms/op
                 listUser·p0.00:   2.257 ms/op
                 listUser·p0.50:   3.727 ms/op
                 listUser·p0.90:   4.080 ms/op
                 listUser·p0.95:   4.547 ms/op
                 listUser·p0.99:   6.832 ms/op
                 listUser·p0.999:  12.698 ms/op
                 listUser·p0.9999: 17.981 ms/op
                 listUser·p1.00:   19.464 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 256140
  mean =      3.747 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 86 
    [ 2.500,  5.000) = 248154 
    [ 5.000,  7.500) = 6066 
    [ 7.500, 10.000) = 1160 
    [10.000, 12.500) = 280 
    [12.500, 15.000) = 186 
    [15.000, 17.500) = 112 
    [17.500, 20.000) = 75 
    [20.000, 22.500) = 21 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.368 ms/op
     p(50.0000) =      3.678 ms/op
     p(90.0000) =      4.006 ms/op
     p(95.0000) =      4.391 ms/op
     p(99.0000) =      7.012 ms/op
     p(99.9000) =     13.809 ms/op
     p(99.9900) =     19.923 ms/op
     p(99.9990) =     21.824 ms/op
     p(99.9999) =     22.151 ms/op
    p(100.0000) =     22.151 ms/op


# Run complete. Total time: 00:13:12

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.931 ± 5.794  ops/ms
ClientPb.existUser                       thrpt       3  10.019 ± 4.763  ops/ms
ClientPb.getUser                         thrpt       3  10.022 ± 4.963  ops/ms
ClientPb.listUser                        thrpt       3   8.588 ± 3.093  ops/ms
ClientPb.createUser                       avgt       3   3.199 ± 0.531   ms/op
ClientPb.existUser                        avgt       3   3.030 ± 0.303   ms/op
ClientPb.getUser                          avgt       3   3.198 ± 0.473   ms/op
ClientPb.listUser                         avgt       3   3.756 ± 0.458   ms/op
ClientPb.createUser                     sample  296392   3.238 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.892           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.166           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.682           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.071           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.521           ms/op
ClientPb.createUser:createUser·p0.999   sample          15.427           ms/op
ClientPb.createUser:createUser·p0.9999  sample          22.097           ms/op
ClientPb.createUser:createUser·p1.00    sample          23.626           ms/op
ClientPb.existUser                      sample  308208   3.113 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.048           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.047           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.391           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.764           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.628           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.977           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.392           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.658           ms/op
ClientPb.getUser                        sample  294774   3.256 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.098           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.183           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.772           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.325           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.999         sample          13.138           ms/op
ClientPb.getUser:getUser·p0.9999        sample          21.135           ms/op
ClientPb.getUser:getUser·p1.00          sample          22.577           ms/op
ClientPb.listUser                       sample  256140   3.747 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.368           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.678           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.006           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.391           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.012           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.809           ms/op
ClientPb.listUser:listUser·p0.9999      sample          19.923           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.151           ms/op
