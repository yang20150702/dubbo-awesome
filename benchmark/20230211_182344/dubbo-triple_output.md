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
# Warmup Iteration   1: 1.554 ops/ms
# Warmup Iteration   2: 3.376 ops/ms
# Warmup Iteration   3: 7.080 ops/ms
Iteration   1: 7.261 ops/ms
Iteration   2: 7.774 ops/ms
Iteration   3: 7.426 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.487 ±(99.9%) 4.777 ops/ms [Average]
  (min, avg, max) = (7.261, 7.487, 7.774), stdev = 0.262
  CI (99.9%): [2.709, 12.264] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.914 ops/ms
# Warmup Iteration   2: 5.931 ops/ms
# Warmup Iteration   3: 7.404 ops/ms
Iteration   1: 7.368 ops/ms
Iteration   2: 7.749 ops/ms
Iteration   3: 7.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.640 ±(99.9%) 4.321 ops/ms [Average]
  (min, avg, max) = (7.368, 7.640, 7.803), stdev = 0.237
  CI (99.9%): [3.319, 11.961] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.044 ops/ms
# Warmup Iteration   2: 6.234 ops/ms
# Warmup Iteration   3: 7.346 ops/ms
Iteration   1: 7.505 ops/ms
Iteration   2: 7.426 ops/ms
Iteration   3: 7.640 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.524 ±(99.9%) 1.978 ops/ms [Average]
  (min, avg, max) = (7.426, 7.524, 7.640), stdev = 0.108
  CI (99.9%): [5.546, 9.502] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 1.937 ops/ms
# Warmup Iteration   2: 5.689 ops/ms
# Warmup Iteration   3: 6.268 ops/ms
Iteration   1: 6.174 ops/ms
Iteration   2: 6.422 ops/ms
Iteration   3: 6.447 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.347 ±(99.9%) 2.754 ops/ms [Average]
  (min, avg, max) = (6.174, 6.347, 6.447), stdev = 0.151
  CI (99.9%): [3.593, 9.102] (assumes normal distribution)


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
# Warmup Iteration   1: 13.360 ±(99.9%) 0.074 ms/op
# Warmup Iteration   2: 5.071 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.489 ±(99.9%) 0.007 ms/op
Iteration   1: 4.145 ±(99.9%) 0.012 ms/op
Iteration   2: 4.309 ±(99.9%) 0.012 ms/op
Iteration   3: 4.375 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.276 ±(99.9%) 2.159 ms/op [Average]
  (min, avg, max) = (4.145, 4.276, 4.375), stdev = 0.118
  CI (99.9%): [2.117, 6.436] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.307 ±(99.9%) 0.034 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 4.237 ±(99.9%) 0.007 ms/op
Iteration   1: 3.988 ±(99.9%) 0.011 ms/op
Iteration   2: 4.074 ±(99.9%) 0.008 ms/op
Iteration   3: 4.090 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.050 ±(99.9%) 1.002 ms/op [Average]
  (min, avg, max) = (3.988, 4.050, 4.090), stdev = 0.055
  CI (99.9%): [3.049, 5.052] (assumes normal distribution)


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
# Warmup Iteration   1: 14.039 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.034 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.307 ±(99.9%) 0.010 ms/op
Iteration   1: 4.371 ±(99.9%) 0.006 ms/op
Iteration   2: 4.361 ±(99.9%) 0.008 ms/op
Iteration   3: 4.164 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.299 ±(99.9%) 2.132 ms/op [Average]
  (min, avg, max) = (4.164, 4.299, 4.371), stdev = 0.117
  CI (99.9%): [2.167, 6.431] (assumes normal distribution)


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
# Warmup Iteration   1: 15.521 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.819 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.146 ±(99.9%) 0.010 ms/op
Iteration   1: 4.952 ±(99.9%) 0.009 ms/op
Iteration   2: 4.834 ±(99.9%) 0.016 ms/op
Iteration   3: 4.879 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.888 ±(99.9%) 1.090 ms/op [Average]
  (min, avg, max) = (4.834, 4.888, 4.952), stdev = 0.060
  CI (99.9%): [3.798, 5.979] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 14.773 ±(99.9%) 0.212 ms/op
# Warmup Iteration   2: 5.543 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.705 ±(99.9%) 0.021 ms/op
Iteration   1: 4.459 ±(99.9%) 0.017 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   4.092 ms/op
                 createUser·p0.90:   5.530 ms/op
                 createUser·p0.95:   6.947 ms/op
                 createUser·p0.99:   9.617 ms/op
                 createUser·p0.999:  18.743 ms/op
                 createUser·p0.9999: 30.338 ms/op
                 createUser·p1.00:   31.293 ms/op

Iteration   2: 3.955 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.671 ms/op
                 createUser·p0.50:   3.887 ms/op
                 createUser·p0.90:   4.268 ms/op
                 createUser·p0.95:   4.563 ms/op
                 createUser·p0.99:   5.571 ms/op
                 createUser·p0.999:  25.690 ms/op
                 createUser·p0.9999: 29.308 ms/op
                 createUser·p1.00:   30.867 ms/op

Iteration   3: 4.197 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.925 ms/op
                 createUser·p0.50:   3.936 ms/op
                 createUser·p0.90:   4.915 ms/op
                 createUser·p0.95:   5.636 ms/op
                 createUser·p0.99:   7.373 ms/op
                 createUser·p0.999:  17.945 ms/op
                 createUser·p0.9999: 31.423 ms/op
                 createUser·p1.00:   32.309 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 228946
  mean =      4.193 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203 
    [ 2.500,  5.000) = 209727 
    [ 5.000,  7.500) = 15345 
    [ 7.500, 10.000) = 2748 
    [10.000, 12.500) = 519 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 9 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.671 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.850 ms/op
     p(95.0000) =      5.620 ms/op
     p(99.0000) =      8.405 ms/op
     p(99.9000) =     18.876 ms/op
     p(99.9900) =     30.736 ms/op
     p(99.9990) =     32.140 ms/op
     p(99.9999) =     32.309 ms/op
    p(100.0000) =     32.309 ms/op


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
# Warmup Iteration   1: 12.835 ±(99.9%) 0.186 ms/op
# Warmup Iteration   2: 4.641 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.193 ±(99.9%) 0.013 ms/op
Iteration   1: 4.109 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   2.134 ms/op
                 existUser·p0.50:   3.883 ms/op
                 existUser·p0.90:   4.686 ms/op
                 existUser·p0.95:   5.571 ms/op
                 existUser·p0.99:   7.890 ms/op
                 existUser·p0.999:  13.206 ms/op
                 existUser·p0.9999: 38.366 ms/op
                 existUser·p1.00:   38.863 ms/op

Iteration   2: 4.234 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.948 ms/op
                 existUser·p0.50:   3.961 ms/op
                 existUser·p0.90:   4.973 ms/op
                 existUser·p0.95:   6.332 ms/op
                 existUser·p0.99:   8.471 ms/op
                 existUser·p0.999:  22.560 ms/op
                 existUser·p0.9999: 29.244 ms/op
                 existUser·p1.00:   30.835 ms/op

Iteration   3: 4.036 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.993 ms/op
                 existUser·p0.50:   3.813 ms/op
                 existUser·p0.90:   4.555 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   7.684 ms/op
                 existUser·p0.999:  14.795 ms/op
                 existUser·p0.9999: 32.738 ms/op
                 existUser·p1.00:   34.210 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 232676
  mean =      4.125 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 215136 
    [ 5.000,  7.500) = 14124 
    [ 7.500, 10.000) = 2149 
    [10.000, 12.500) = 561 
    [12.500, 15.000) = 249 
    [15.000, 17.500) = 6 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 17 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 47 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 14 
    [35.000, 37.500) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.948 ms/op
     p(50.0000) =      3.883 ms/op
     p(90.0000) =      4.719 ms/op
     p(95.0000) =      5.530 ms/op
     p(99.0000) =      8.104 ms/op
     p(99.9000) =     15.029 ms/op
     p(99.9900) =     36.831 ms/op
     p(99.9990) =     38.776 ms/op
     p(99.9999) =     38.863 ms/op
    p(100.0000) =     38.863 ms/op


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
# Warmup Iteration   1: 13.984 ±(99.9%) 0.218 ms/op
# Warmup Iteration   2: 5.365 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 4.241 ±(99.9%) 0.014 ms/op
Iteration   1: 4.282 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.612 ms/op
                 getUser·p0.50:   4.051 ms/op
                 getUser·p0.90:   4.989 ms/op
                 getUser·p0.95:   5.710 ms/op
                 getUser·p0.99:   8.503 ms/op
                 getUser·p0.999:  21.901 ms/op
                 getUser·p0.9999: 27.820 ms/op
                 getUser·p1.00:   27.853 ms/op

Iteration   2: 4.449 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   2.126 ms/op
                 getUser·p0.50:   4.182 ms/op
                 getUser·p0.90:   5.202 ms/op
                 getUser·p0.95:   6.373 ms/op
                 getUser·p0.99:   8.765 ms/op
                 getUser·p0.999:  28.213 ms/op
                 getUser·p0.9999: 34.643 ms/op
                 getUser·p1.00:   35.783 ms/op

Iteration   3: 4.192 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.212 ms/op
                 getUser·p0.50:   3.981 ms/op
                 getUser·p0.90:   4.850 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   7.683 ms/op
                 getUser·p0.999:  12.218 ms/op
                 getUser·p0.9999: 35.914 ms/op
                 getUser·p1.00:   36.241 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 223002
  mean =      4.305 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 39 
    [ 2.500,  5.000) = 200420 
    [ 5.000,  7.500) = 18337 
    [ 7.500, 10.000) = 3215 
    [10.000, 12.500) = 574 
    [12.500, 15.000) = 140 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 20 
    [22.500, 25.000) = 36 
    [25.000, 27.500) = 44 
    [27.500, 30.000) = 77 
    [30.000, 32.500) = 17 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.612 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      5.005 ms/op
     p(95.0000) =      5.743 ms/op
     p(99.0000) =      8.372 ms/op
     p(99.9000) =     23.724 ms/op
     p(99.9900) =     35.566 ms/op
     p(99.9990) =     36.176 ms/op
     p(99.9999) =     36.241 ms/op
    p(100.0000) =     36.241 ms/op


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
# Warmup Iteration   1: 16.318 ±(99.9%) 0.257 ms/op
# Warmup Iteration   2: 5.839 ±(99.9%) 0.033 ms/op
# Warmup Iteration   3: 5.285 ±(99.9%) 0.020 ms/op
Iteration   1: 5.182 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.327 ms/op
                 listUser·p0.50:   4.874 ms/op
                 listUser·p0.90:   6.046 ms/op
                 listUser·p0.95:   7.856 ms/op
                 listUser·p0.99:   9.896 ms/op
                 listUser·p0.999:  26.059 ms/op
                 listUser·p0.9999: 30.377 ms/op
                 listUser·p1.00:   31.818 ms/op

Iteration   2: 5.047 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   0.945 ms/op
                 listUser·p0.50:   4.784 ms/op
                 listUser·p0.90:   5.710 ms/op
                 listUser·p0.95:   6.947 ms/op
                 listUser·p0.99:   9.798 ms/op
                 listUser·p0.999:  19.747 ms/op
                 listUser·p0.9999: 25.122 ms/op
                 listUser·p1.00:   26.477 ms/op

Iteration   3: 4.916 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.747 ms/op
                 listUser·p0.50:   4.760 ms/op
                 listUser·p0.90:   5.423 ms/op
                 listUser·p0.95:   5.882 ms/op
                 listUser·p0.99:   8.700 ms/op
                 listUser·p0.999:  18.611 ms/op
                 listUser·p0.9999: 21.135 ms/op
                 listUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 190111
  mean =      5.046 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 17 
    [ 2.500,  5.000) = 126148 
    [ 5.000,  7.500) = 56454 
    [ 7.500, 10.000) = 6003 
    [10.000, 12.500) = 812 
    [12.500, 15.000) = 242 
    [15.000, 17.500) = 126 
    [17.500, 20.000) = 90 
    [20.000, 22.500) = 64 
    [22.500, 25.000) = 69 
    [25.000, 27.500) = 50 
    [27.500, 30.000) = 30 
    [30.000, 32.500) = 6 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.945 ms/op
     p(50.0000) =      4.801 ms/op
     p(90.0000) =      5.669 ms/op
     p(95.0000) =      6.783 ms/op
     p(99.0000) =      9.503 ms/op
     p(99.9000) =     20.706 ms/op
     p(99.9900) =     28.770 ms/op
     p(99.9990) =     30.932 ms/op
     p(99.9999) =     31.818 ms/op
    p(100.0000) =     31.818 ms/op


# Run complete. Total time: 00:13:14

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.487 ± 4.777  ops/ms
ClientPb.existUser                       thrpt       3   7.640 ± 4.321  ops/ms
ClientPb.getUser                         thrpt       3   7.524 ± 1.978  ops/ms
ClientPb.listUser                        thrpt       3   6.347 ± 2.754  ops/ms
ClientPb.createUser                       avgt       3   4.276 ± 2.159   ms/op
ClientPb.existUser                        avgt       3   4.050 ± 1.002   ms/op
ClientPb.getUser                          avgt       3   4.299 ± 2.132   ms/op
ClientPb.listUser                         avgt       3   4.888 ± 1.090   ms/op
ClientPb.createUser                     sample  228946   4.193 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.671           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.620           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.405           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.876           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.736           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.309           ms/op
ClientPb.existUser                      sample  232676   4.125 ± 0.008   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.948           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.883           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.719           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.530           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.104           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.029           ms/op
ClientPb.existUser:existUser·p0.9999    sample          36.831           ms/op
ClientPb.existUser:existUser·p1.00      sample          38.863           ms/op
ClientPb.getUser                        sample  223002   4.305 ± 0.009   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.612           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.90          sample           5.005           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.743           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.372           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.724           ms/op
ClientPb.getUser:getUser·p0.9999        sample          35.566           ms/op
ClientPb.getUser:getUser·p1.00          sample          36.241           ms/op
ClientPb.listUser                       sample  190111   5.046 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.945           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.801           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.669           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.783           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.503           ms/op
ClientPb.listUser:listUser·p0.999       sample          20.706           ms/op
ClientPb.listUser:listUser·p0.9999      sample          28.770           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.818           ms/op
