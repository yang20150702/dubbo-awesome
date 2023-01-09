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
# Warmup Iteration   1: 2.090 ops/ms
# Warmup Iteration   2: 5.355 ops/ms
# Warmup Iteration   3: 8.773 ops/ms
Iteration   1: 9.275 ops/ms
Iteration   2: 9.424 ops/ms
Iteration   3: 9.533 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.411 ±(99.9%) 2.367 ops/ms [Average]
  (min, avg, max) = (9.275, 9.411, 9.533), stdev = 0.130
  CI (99.9%): [7.044, 11.778] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 2.892 ops/ms
# Warmup Iteration   2: 8.623 ops/ms
# Warmup Iteration   3: 9.470 ops/ms
Iteration   1: 9.794 ops/ms
Iteration   2: 9.599 ops/ms
Iteration   3: 9.837 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.743 ±(99.9%) 2.313 ops/ms [Average]
  (min, avg, max) = (9.599, 9.743, 9.837), stdev = 0.127
  CI (99.9%): [7.431, 12.056] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:10:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.900 ops/ms
# Warmup Iteration   2: 8.114 ops/ms
# Warmup Iteration   3: 9.051 ops/ms
Iteration   1: 9.685 ops/ms
Iteration   2: 9.410 ops/ms
Iteration   3: 9.458 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.518 ±(99.9%) 2.679 ops/ms [Average]
  (min, avg, max) = (9.410, 9.518, 9.685), stdev = 0.147
  CI (99.9%): [6.838, 12.197] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:52
# Fork: 1 of 1
# Warmup Iteration   1: 2.931 ops/ms
# Warmup Iteration   2: 7.362 ops/ms
# Warmup Iteration   3: 7.981 ops/ms
Iteration   1: 7.819 ops/ms
Iteration   2: 8.159 ops/ms
Iteration   3: 8.320 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.099 ±(99.9%) 4.668 ops/ms [Average]
  (min, avg, max) = (7.819, 8.099, 8.320), stdev = 0.256
  CI (99.9%): [3.431, 12.767] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:44
# Fork: 1 of 1
# Warmup Iteration   1: 10.098 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.806 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 3.556 ±(99.9%) 0.009 ms/op
Iteration   1: 3.444 ±(99.9%) 0.006 ms/op
Iteration   2: 3.377 ±(99.9%) 0.006 ms/op
Iteration   3: 3.337 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.386 ±(99.9%) 0.992 ms/op [Average]
  (min, avg, max) = (3.337, 3.386, 3.444), stdev = 0.054
  CI (99.9%): [2.394, 4.378] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 8.320 ±(99.9%) 0.023 ms/op
# Warmup Iteration   2: 3.598 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.462 ±(99.9%) 0.007 ms/op
Iteration   1: 3.341 ±(99.9%) 0.008 ms/op
Iteration   2: 3.214 ±(99.9%) 0.005 ms/op
Iteration   3: 3.358 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.304 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (3.214, 3.304, 3.358), stdev = 0.079
  CI (99.9%): [1.868, 4.740] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 9.503 ±(99.9%) 0.035 ms/op
# Warmup Iteration   2: 3.746 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.638 ±(99.9%) 0.004 ms/op
Iteration   1: 3.415 ±(99.9%) 0.008 ms/op
Iteration   2: 3.363 ±(99.9%) 0.009 ms/op
Iteration   3: 3.423 ±(99.9%) 0.002 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.400 ±(99.9%) 0.592 ms/op [Average]
  (min, avg, max) = (3.363, 3.400, 3.423), stdev = 0.032
  CI (99.9%): [2.809, 3.992] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 11.316 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.413 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.980 ±(99.9%) 0.010 ms/op
Iteration   1: 4.029 ±(99.9%) 0.007 ms/op
Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
Iteration   3: 3.905 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.961 ±(99.9%) 1.150 ms/op [Average]
  (min, avg, max) = (3.905, 3.961, 4.029), stdev = 0.063
  CI (99.9%): [2.812, 5.111] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.370 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 4.134 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.647 ±(99.9%) 0.013 ms/op
Iteration   1: 3.408 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.509 ms/op
                 createUser·p0.50:   3.310 ms/op
                 createUser·p0.90:   3.793 ms/op
                 createUser·p0.95:   4.030 ms/op
                 createUser·p0.99:   5.849 ms/op
                 createUser·p0.999:  20.844 ms/op
                 createUser·p0.9999: 26.360 ms/op
                 createUser·p1.00:   29.229 ms/op

Iteration   2: 3.416 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.225 ms/op
                 createUser·p0.50:   3.305 ms/op
                 createUser·p0.90:   3.801 ms/op
                 createUser·p0.95:   4.018 ms/op
                 createUser·p0.99:   5.775 ms/op
                 createUser·p0.999:  21.640 ms/op
                 createUser·p0.9999: 28.780 ms/op
                 createUser·p1.00:   29.458 ms/op

Iteration   3: 3.438 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.409 ms/op
                 createUser·p0.50:   3.322 ms/op
                 createUser·p0.90:   3.785 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.898 ms/op
                 createUser·p0.999:  16.479 ms/op
                 createUser·p0.9999: 25.616 ms/op
                 createUser·p1.00:   53.543 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 280099
  mean =      3.420 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 274266 
    [ 5.000, 10.000) = 5431 
    [10.000, 15.000) = 110 
    [15.000, 20.000) = 54 
    [20.000, 25.000) = 143 
    [25.000, 30.000) = 91 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 0 
    [45.000, 50.000) = 0 
    [50.000, 55.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.225 ms/op
     p(50.0000) =      3.314 ms/op
     p(90.0000) =      3.793 ms/op
     p(95.0000) =      4.051 ms/op
     p(99.0000) =      6.062 ms/op
     p(99.9000) =     17.265 ms/op
     p(99.9900) =     27.721 ms/op
     p(99.9990) =     52.153 ms/op
     p(99.9999) =     53.543 ms/op
    p(100.0000) =     53.543 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.304 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 3.692 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.289 ±(99.9%) 0.007 ms/op
Iteration   1: 3.356 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.301 ms/op
                 existUser·p0.90:   3.883 ms/op
                 existUser·p0.95:   4.268 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  8.304 ms/op
                 existUser·p0.9999: 26.083 ms/op
                 existUser·p1.00:   26.640 ms/op

Iteration   2: 3.330 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   0.793 ms/op
                 existUser·p0.50:   3.269 ms/op
                 existUser·p0.90:   3.678 ms/op
                 existUser·p0.95:   4.104 ms/op
                 existUser·p0.99:   5.513 ms/op
                 existUser·p0.999:  20.164 ms/op
                 existUser·p0.9999: 24.478 ms/op
                 existUser·p1.00:   25.690 ms/op

Iteration   3: 3.282 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.683 ms/op
                 existUser·p0.50:   3.162 ms/op
                 existUser·p0.90:   3.555 ms/op
                 existUser·p0.95:   3.850 ms/op
                 existUser·p0.99:   5.603 ms/op
                 existUser·p0.999:  18.605 ms/op
                 existUser·p0.9999: 40.894 ms/op
                 existUser·p1.00:   43.385 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 288929
  mean =      3.322 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 283637 
    [ 5.000, 10.000) = 4899 
    [10.000, 15.000) = 111 
    [15.000, 20.000) = 27 
    [20.000, 25.000) = 154 
    [25.000, 30.000) = 40 
    [30.000, 35.000) = 29 
    [35.000, 40.000) = 17 
    [40.000, 45.000) = 15 

  Percentiles, ms/op:
      p(0.0000) =      0.793 ms/op
     p(50.0000) =      3.244 ms/op
     p(90.0000) =      3.682 ms/op
     p(95.0000) =      4.121 ms/op
     p(99.0000) =      5.546 ms/op
     p(99.9000) =     13.813 ms/op
     p(99.9900) =     39.066 ms/op
     p(99.9990) =     42.482 ms/op
     p(99.9999) =     43.385 ms/op
    p(100.0000) =     43.385 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 9.292 ±(99.9%) 0.135 ms/op
# Warmup Iteration   2: 3.772 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.585 ±(99.9%) 0.011 ms/op
Iteration   1: 3.410 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.882 ms/op
                 getUser·p0.50:   3.273 ms/op
                 getUser·p0.90:   3.826 ms/op
                 getUser·p0.95:   4.108 ms/op
                 getUser·p0.99:   6.349 ms/op
                 getUser·p0.999:  19.813 ms/op
                 getUser·p0.9999: 22.970 ms/op
                 getUser·p1.00:   23.691 ms/op

Iteration   2: 3.337 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.655 ms/op
                 getUser·p0.50:   3.228 ms/op
                 getUser·p0.90:   3.670 ms/op
                 getUser·p0.95:   4.018 ms/op
                 getUser·p0.99:   6.291 ms/op
                 getUser·p0.999:  21.740 ms/op
                 getUser·p0.9999: 23.790 ms/op
                 getUser·p1.00:   24.674 ms/op

Iteration   3: 3.403 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.393 ms/op
                 getUser·p0.50:   3.318 ms/op
                 getUser·p0.90:   3.736 ms/op
                 getUser·p0.95:   3.887 ms/op
                 getUser·p0.99:   5.448 ms/op
                 getUser·p0.999:  18.202 ms/op
                 getUser·p0.9999: 26.529 ms/op
                 getUser·p1.00:   27.034 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 283471
  mean =      3.383 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5450 
    [ 2.500,  5.000) = 272485 
    [ 5.000,  7.500) = 4657 
    [ 7.500, 10.000) = 516 
    [10.000, 12.500) = 74 
    [12.500, 15.000) = 1 
    [15.000, 17.500) = 2 
    [17.500, 20.000) = 9 
    [20.000, 22.500) = 124 
    [22.500, 25.000) = 130 
    [25.000, 27.500) = 23 

  Percentiles, ms/op:
      p(0.0000) =      1.393 ms/op
     p(50.0000) =      3.269 ms/op
     p(90.0000) =      3.756 ms/op
     p(95.0000) =      3.994 ms/op
     p(99.0000) =      5.923 ms/op
     p(99.9000) =     19.522 ms/op
     p(99.9900) =     24.815 ms/op
     p(99.9990) =     26.913 ms/op
     p(99.9999) =     27.034 ms/op
    p(100.0000) =     27.034 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 10.591 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.265 ±(99.9%) 0.016 ms/op
# Warmup Iteration   3: 4.018 ±(99.9%) 0.013 ms/op
Iteration   1: 3.910 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   1.782 ms/op
                 listUser·p0.50:   3.789 ms/op
                 listUser·p0.90:   4.227 ms/op
                 listUser·p0.95:   4.620 ms/op
                 listUser·p0.99:   6.873 ms/op
                 listUser·p0.999:  17.870 ms/op
                 listUser·p0.9999: 23.450 ms/op
                 listUser·p1.00:   25.199 ms/op

Iteration   2: 3.909 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.302 ms/op
                 listUser·p0.50:   3.797 ms/op
                 listUser·p0.90:   4.194 ms/op
                 listUser·p0.95:   4.424 ms/op
                 listUser·p0.99:   7.307 ms/op
                 listUser·p0.999:  15.158 ms/op
                 listUser·p0.9999: 18.475 ms/op
                 listUser·p1.00:   19.595 ms/op

Iteration   3: 4.009 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.253 ms/op
                 listUser·p0.50:   3.899 ms/op
                 listUser·p0.90:   4.317 ms/op
                 listUser·p0.95:   4.530 ms/op
                 listUser·p0.99:   7.193 ms/op
                 listUser·p0.999:  14.979 ms/op
                 listUser·p0.9999: 17.990 ms/op
                 listUser·p1.00:   18.022 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 243384
  mean =      3.943 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 236043 
    [ 5.000,  7.500) = 5439 
    [ 7.500, 10.000) = 1116 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 217 
    [15.000, 17.500) = 173 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 25 
    [25.000, 27.500) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.782 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.260 ms/op
     p(95.0000) =      4.522 ms/op
     p(99.0000) =      7.094 ms/op
     p(99.9000) =     16.122 ms/op
     p(99.9900) =     22.927 ms/op
     p(99.9990) =     25.119 ms/op
     p(99.9999) =     25.199 ms/op
    p(100.0000) =     25.199 ms/op


# Run complete. Total time: 00:13:09

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.411 ± 2.367  ops/ms
ClientPb.existUser                       thrpt       3   9.743 ± 2.313  ops/ms
ClientPb.getUser                         thrpt       3   9.518 ± 2.679  ops/ms
ClientPb.listUser                        thrpt       3   8.099 ± 4.668  ops/ms
ClientPb.createUser                       avgt       3   3.386 ± 0.992   ms/op
ClientPb.existUser                        avgt       3   3.304 ± 1.436   ms/op
ClientPb.getUser                          avgt       3   3.400 ± 0.592   ms/op
ClientPb.listUser                         avgt       3   3.961 ± 1.150   ms/op
ClientPb.createUser                     sample  280099   3.420 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.225           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.314           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.793           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.051           ms/op
ClientPb.createUser:createUser·p0.99    sample           6.062           ms/op
ClientPb.createUser:createUser·p0.999   sample          17.265           ms/op
ClientPb.createUser:createUser·p0.9999  sample          27.721           ms/op
ClientPb.createUser:createUser·p1.00    sample          53.543           ms/op
ClientPb.existUser                      sample  288929   3.322 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.793           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.244           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.682           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.121           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.546           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.813           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.066           ms/op
ClientPb.existUser:existUser·p1.00      sample          43.385           ms/op
ClientPb.getUser                        sample  283471   3.383 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.393           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.269           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.756           ms/op
ClientPb.getUser:getUser·p0.95          sample           3.994           ms/op
ClientPb.getUser:getUser·p0.99          sample           5.923           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.522           ms/op
ClientPb.getUser:getUser·p0.9999        sample          24.815           ms/op
ClientPb.getUser:getUser·p1.00          sample          27.034           ms/op
ClientPb.listUser                       sample  243384   3.943 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.782           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.813           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.260           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.522           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.094           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.122           ms/op
ClientPb.listUser:listUser·p0.9999      sample          22.927           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.199           ms/op
