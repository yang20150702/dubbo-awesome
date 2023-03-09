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
# Warmup Iteration   1: 2.116 ops/ms
# Warmup Iteration   2: 4.947 ops/ms
# Warmup Iteration   3: 8.358 ops/ms
Iteration   1: 9.058 ops/ms
Iteration   2: 9.285 ops/ms
Iteration   3: 9.553 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.299 ±(99.9%) 4.517 ops/ms [Average]
  (min, avg, max) = (9.058, 9.299, 9.553), stdev = 0.248
  CI (99.9%): [4.781, 13.816] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:11:58
# Fork: 1 of 1
# Warmup Iteration   1: 3.433 ops/ms
# Warmup Iteration   2: 8.812 ops/ms
# Warmup Iteration   3: 9.392 ops/ms
Iteration   1: 9.634 ops/ms
Iteration   2: 10.114 ops/ms
Iteration   3: 9.727 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  9.825 ±(99.9%) 4.643 ops/ms [Average]
  (min, avg, max) = (9.634, 9.825, 10.114), stdev = 0.255
  CI (99.9%): [5.182, 14.468] (assumes normal distribution)


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
# Warmup Iteration   1: 3.188 ops/ms
# Warmup Iteration   2: 8.872 ops/ms
# Warmup Iteration   3: 9.278 ops/ms
Iteration   1: 9.627 ops/ms
Iteration   2: 9.136 ops/ms
Iteration   3: 9.445 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  9.403 ±(99.9%) 4.525 ops/ms [Average]
  (min, avg, max) = (9.136, 9.403, 9.627), stdev = 0.248
  CI (99.9%): [4.878, 13.927] (assumes normal distribution)


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
# Warmup Iteration   1: 2.793 ops/ms
# Warmup Iteration   2: 7.320 ops/ms
# Warmup Iteration   3: 7.787 ops/ms
Iteration   1: 8.270 ops/ms
Iteration   2: 8.021 ops/ms
Iteration   3: 8.104 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.132 ±(99.9%) 2.310 ops/ms [Average]
  (min, avg, max) = (8.021, 8.132, 8.270), stdev = 0.127
  CI (99.9%): [5.822, 10.442] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:45
# Fork: 1 of 1
# Warmup Iteration   1: 11.771 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 3.904 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.538 ±(99.9%) 0.007 ms/op
Iteration   1: 3.455 ±(99.9%) 0.005 ms/op
Iteration   2: 3.412 ±(99.9%) 0.009 ms/op
Iteration   3: 3.325 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.397 ±(99.9%) 1.206 ms/op [Average]
  (min, avg, max) = (3.325, 3.397, 3.455), stdev = 0.066
  CI (99.9%): [2.191, 4.604] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:38
# Fork: 1 of 1
# Warmup Iteration   1: 8.604 ±(99.9%) 0.021 ms/op
# Warmup Iteration   2: 3.684 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.290 ±(99.9%) 0.007 ms/op
Iteration   1: 3.274 ±(99.9%) 0.011 ms/op
Iteration   2: 3.308 ±(99.9%) 0.005 ms/op
Iteration   3: 3.195 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.259 ±(99.9%) 1.052 ms/op [Average]
  (min, avg, max) = (3.195, 3.259, 3.308), stdev = 0.058
  CI (99.9%): [2.207, 4.311] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:32
# Fork: 1 of 1
# Warmup Iteration   1: 9.459 ±(99.9%) 0.037 ms/op
# Warmup Iteration   2: 3.636 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 3.616 ±(99.9%) 0.005 ms/op
Iteration   1: 3.430 ±(99.9%) 0.006 ms/op
Iteration   2: 3.488 ±(99.9%) 0.005 ms/op
Iteration   3: 3.434 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.451 ±(99.9%) 0.595 ms/op [Average]
  (min, avg, max) = (3.430, 3.451, 3.488), stdev = 0.033
  CI (99.9%): [2.856, 4.046] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:27
# Fork: 1 of 1
# Warmup Iteration   1: 11.244 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.414 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 4.287 ±(99.9%) 0.005 ms/op
Iteration   1: 3.976 ±(99.9%) 0.010 ms/op
Iteration   2: 3.954 ±(99.9%) 0.013 ms/op
Iteration   3: 4.000 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.976 ±(99.9%) 0.413 ms/op [Average]
  (min, avg, max) = (3.954, 3.976, 4.000), stdev = 0.023
  CI (99.9%): [3.564, 4.389] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:21
# Fork: 1 of 1
# Warmup Iteration   1: 11.013 ±(99.9%) 0.125 ms/op
# Warmup Iteration   2: 4.237 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.668 ±(99.9%) 0.012 ms/op
Iteration   1: 3.397 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.454 ms/op
                 createUser·p0.50:   3.244 ms/op
                 createUser·p0.90:   3.830 ms/op
                 createUser·p0.95:   4.121 ms/op
                 createUser·p0.99:   6.077 ms/op
                 createUser·p0.999:  21.426 ms/op
                 createUser·p0.9999: 25.513 ms/op
                 createUser·p1.00:   25.985 ms/op

Iteration   2: 3.367 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.630 ms/op
                 createUser·p0.50:   3.277 ms/op
                 createUser·p0.90:   3.674 ms/op
                 createUser·p0.95:   4.035 ms/op
                 createUser·p0.99:   5.714 ms/op
                 createUser·p0.999:  23.986 ms/op
                 createUser·p0.9999: 26.394 ms/op
                 createUser·p1.00:   27.001 ms/op

Iteration   3: 3.544 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   0.878 ms/op
                 createUser·p0.50:   3.445 ms/op
                 createUser·p0.90:   4.092 ms/op
                 createUser·p0.95:   4.637 ms/op
                 createUser·p0.99:   6.167 ms/op
                 createUser·p0.999:  8.975 ms/op
                 createUser·p0.9999: 31.849 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 279486
  mean =      3.434 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10008 
    [ 2.500,  5.000) = 261247 
    [ 5.000,  7.500) = 7397 
    [ 7.500, 10.000) = 528 
    [10.000, 12.500) = 18 
    [12.500, 15.000) = 0 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 143 
    [25.000, 27.500) = 101 
    [27.500, 30.000) = 0 
    [30.000, 32.500) = 32 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.878 ms/op
     p(50.0000) =      3.342 ms/op
     p(90.0000) =      3.875 ms/op
     p(95.0000) =      4.260 ms/op
     p(99.0000) =      5.939 ms/op
     p(99.9000) =     22.220 ms/op
     p(99.9900) =     31.293 ms/op
     p(99.9990) =     32.067 ms/op
     p(99.9999) =     32.342 ms/op
    p(100.0000) =     32.342 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:16
# Fork: 1 of 1
# Warmup Iteration   1: 9.514 ±(99.9%) 0.121 ms/op
# Warmup Iteration   2: 3.668 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 3.364 ±(99.9%) 0.008 ms/op
Iteration   1: 3.399 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.188 ms/op
                 existUser·p0.50:   3.355 ms/op
                 existUser·p0.90:   3.793 ms/op
                 existUser·p0.95:   4.137 ms/op
                 existUser·p0.99:   5.784 ms/op
                 existUser·p0.999:  22.643 ms/op
                 existUser·p0.9999: 26.992 ms/op
                 existUser·p1.00:   27.492 ms/op

Iteration   2: 3.388 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   1.413 ms/op
                 existUser·p0.50:   3.256 ms/op
                 existUser·p0.90:   3.752 ms/op
                 existUser·p0.95:   4.125 ms/op
                 existUser·p0.99:   6.054 ms/op
                 existUser·p0.999:  22.957 ms/op
                 existUser·p0.9999: 26.331 ms/op
                 existUser·p1.00:   26.608 ms/op

Iteration   3: 3.305 ±(99.9%) 0.009 ms/op
                 existUser·p0.00:   1.085 ms/op
                 existUser·p0.50:   3.219 ms/op
                 existUser·p0.90:   3.559 ms/op
                 existUser·p0.95:   3.867 ms/op
                 existUser·p0.99:   5.816 ms/op
                 existUser·p0.999:  16.677 ms/op
                 existUser·p0.9999: 28.737 ms/op
                 existUser·p1.00:   29.721 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 285389
  mean =      3.363 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13354 
    [ 2.500,  5.000) = 265871 
    [ 5.000,  7.500) = 5088 
    [ 7.500, 10.000) = 600 
    [10.000, 12.500) = 103 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 30 
    [22.500, 25.000) = 120 
    [25.000, 27.500) = 114 

  Percentiles, ms/op:
      p(0.0000) =      1.085 ms/op
     p(50.0000) =      3.297 ms/op
     p(90.0000) =      3.703 ms/op
     p(95.0000) =      4.084 ms/op
     p(99.0000) =      5.825 ms/op
     p(99.9000) =     20.061 ms/op
     p(99.9900) =     27.127 ms/op
     p(99.9990) =     29.168 ms/op
     p(99.9999) =     29.721 ms/op
    p(100.0000) =     29.721 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:10
# Fork: 1 of 1
# Warmup Iteration   1: 10.999 ±(99.9%) 0.141 ms/op
# Warmup Iteration   2: 3.947 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.477 ±(99.9%) 0.009 ms/op
Iteration   1: 3.481 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.225 ms/op
                 getUser·p0.50:   3.301 ms/op
                 getUser·p0.90:   3.953 ms/op
                 getUser·p0.95:   4.588 ms/op
                 getUser·p0.99:   6.717 ms/op
                 getUser·p0.999:  20.928 ms/op
                 getUser·p0.9999: 29.665 ms/op
                 getUser·p1.00:   30.441 ms/op

Iteration   2: 3.387 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.256 ms/op
                 getUser·p0.90:   3.662 ms/op
                 getUser·p0.95:   3.908 ms/op
                 getUser·p0.99:   6.205 ms/op
                 getUser·p0.999:  21.924 ms/op
                 getUser·p0.9999: 26.069 ms/op
                 getUser·p1.00:   26.804 ms/op

Iteration   3: 3.501 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.810 ms/op
                 getUser·p0.50:   3.379 ms/op
                 getUser·p0.90:   4.063 ms/op
                 getUser·p0.95:   4.489 ms/op
                 getUser·p0.99:   6.259 ms/op
                 getUser·p0.999:  18.547 ms/op
                 getUser·p0.9999: 25.947 ms/op
                 getUser·p1.00:   27.787 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 277693
  mean =      3.456 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10767 
    [ 2.500,  5.000) = 257841 
    [ 5.000,  7.500) = 7724 
    [ 7.500, 10.000) = 862 
    [10.000, 12.500) = 122 
    [12.500, 15.000) = 87 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 110 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.322 ms/op
     p(90.0000) =      3.903 ms/op
     p(95.0000) =      4.350 ms/op
     p(99.0000) =      6.439 ms/op
     p(99.9000) =     18.725 ms/op
     p(99.9900) =     28.276 ms/op
     p(99.9990) =     30.383 ms/op
     p(99.9999) =     30.441 ms/op
    p(100.0000) =     30.441 ms/op


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
# Warmup Iteration   1: 10.222 ±(99.9%) 0.152 ms/op
# Warmup Iteration   2: 4.449 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 4.112 ±(99.9%) 0.014 ms/op
Iteration   1: 3.970 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   1.049 ms/op
                 listUser·p0.50:   3.846 ms/op
                 listUser·p0.90:   4.276 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.014 ms/op
                 listUser·p0.999:  20.785 ms/op
                 listUser·p0.9999: 24.204 ms/op
                 listUser·p1.00:   25.461 ms/op

Iteration   2: 4.118 ±(99.9%) 0.011 ms/op
                 listUser·p0.00:   2.478 ms/op
                 listUser·p0.50:   3.990 ms/op
                 listUser·p0.90:   4.432 ms/op
                 listUser·p0.95:   4.661 ms/op
                 listUser·p0.99:   8.086 ms/op
                 listUser·p0.999:  17.610 ms/op
                 listUser·p0.9999: 19.694 ms/op
                 listUser·p1.00:   20.152 ms/op

Iteration   3: 3.982 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.322 ms/op
                 listUser·p0.50:   3.895 ms/op
                 listUser·p0.90:   4.252 ms/op
                 listUser·p0.95:   4.563 ms/op
                 listUser·p0.99:   7.004 ms/op
                 listUser·p0.999:  15.970 ms/op
                 listUser·p0.9999: 16.842 ms/op
                 listUser·p1.00:   16.908 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 238568
  mean =      4.022 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 18 
    [ 2.500,  5.000) = 231568 
    [ 5.000,  7.500) = 4702 
    [ 7.500, 10.000) = 1478 
    [10.000, 12.500) = 246 
    [12.500, 15.000) = 134 
    [15.000, 17.500) = 238 
    [17.500, 20.000) = 87 
    [20.000, 22.500) = 57 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.049 ms/op
     p(50.0000) =      3.895 ms/op
     p(90.0000) =      4.358 ms/op
     p(95.0000) =      4.604 ms/op
     p(99.0000) =      7.381 ms/op
     p(99.9000) =     16.679 ms/op
     p(99.9900) =     23.401 ms/op
     p(99.9990) =     24.619 ms/op
     p(99.9999) =     25.461 ms/op
    p(100.0000) =     25.461 ms/op


# Run complete. Total time: 00:13:06

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.299 ± 4.517  ops/ms
ClientPb.existUser                       thrpt       3   9.825 ± 4.643  ops/ms
ClientPb.getUser                         thrpt       3   9.403 ± 4.525  ops/ms
ClientPb.listUser                        thrpt       3   8.132 ± 2.310  ops/ms
ClientPb.createUser                       avgt       3   3.397 ± 1.206   ms/op
ClientPb.existUser                        avgt       3   3.259 ± 1.052   ms/op
ClientPb.getUser                          avgt       3   3.451 ± 0.595   ms/op
ClientPb.listUser                         avgt       3   3.976 ± 0.413   ms/op
ClientPb.createUser                     sample  279486   3.434 ± 0.006   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.878           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.342           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.875           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.260           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.939           ms/op
ClientPb.createUser:createUser·p0.999   sample          22.220           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.293           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.342           ms/op
ClientPb.existUser                      sample  285389   3.363 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.085           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.297           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.703           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.084           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.825           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.061           ms/op
ClientPb.existUser:existUser·p0.9999    sample          27.127           ms/op
ClientPb.existUser:existUser·p1.00      sample          29.721           ms/op
ClientPb.getUser                        sample  277693   3.456 ± 0.006   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.194           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.322           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.903           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.350           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.439           ms/op
ClientPb.getUser:getUser·p0.999         sample          18.725           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.276           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.441           ms/op
ClientPb.listUser                       sample  238568   4.022 ± 0.006   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.049           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.895           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.358           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.381           ms/op
ClientPb.listUser:listUser·p0.999       sample          16.679           ms/op
ClientPb.listUser:listUser·p0.9999      sample          23.401           ms/op
ClientPb.listUser:listUser·p1.00        sample          25.461           ms/op
