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
# Warmup Iteration   1: 1.764 ops/ms
# Warmup Iteration   2: 4.082 ops/ms
# Warmup Iteration   3: 7.547 ops/ms
Iteration   1: 7.479 ops/ms
Iteration   2: 7.890 ops/ms
Iteration   3: 8.128 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.832 ±(99.9%) 5.987 ops/ms [Average]
  (min, avg, max) = (7.479, 7.832, 8.128), stdev = 0.328
  CI (99.9%): [1.846, 13.819] (assumes normal distribution)


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
# Warmup Iteration   1: 2.367 ops/ms
# Warmup Iteration   2: 6.696 ops/ms
# Warmup Iteration   3: 8.133 ops/ms
Iteration   1: 8.374 ops/ms
Iteration   2: 8.351 ops/ms
Iteration   3: 8.490 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.405 ±(99.9%) 1.361 ops/ms [Average]
  (min, avg, max) = (8.351, 8.405, 8.490), stdev = 0.075
  CI (99.9%): [7.043, 9.766] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.440 ops/ms
# Warmup Iteration   2: 6.750 ops/ms
# Warmup Iteration   3: 7.743 ops/ms
Iteration   1: 8.126 ops/ms
Iteration   2: 8.441 ops/ms
Iteration   3: 8.222 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.263 ±(99.9%) 2.943 ops/ms [Average]
  (min, avg, max) = (8.126, 8.263, 8.441), stdev = 0.161
  CI (99.9%): [5.320, 11.206] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 2.230 ops/ms
# Warmup Iteration   2: 5.995 ops/ms
# Warmup Iteration   3: 6.898 ops/ms
Iteration   1: 6.765 ops/ms
Iteration   2: 6.712 ops/ms
Iteration   3: 6.880 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.786 ±(99.9%) 1.567 ops/ms [Average]
  (min, avg, max) = (6.712, 6.786, 6.880), stdev = 0.086
  CI (99.9%): [5.219, 8.353] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:49
# Fork: 1 of 1
# Warmup Iteration   1: 12.599 ±(99.9%) 0.038 ms/op
# Warmup Iteration   2: 4.324 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.327 ±(99.9%) 0.006 ms/op
Iteration   1: 3.981 ±(99.9%) 0.010 ms/op
Iteration   2: 3.879 ±(99.9%) 0.009 ms/op
Iteration   3: 3.818 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.893 ±(99.9%) 1.498 ms/op [Average]
  (min, avg, max) = (3.818, 3.893, 3.981), stdev = 0.082
  CI (99.9%): [2.395, 5.391] (assumes normal distribution)


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
# Warmup Iteration   1: 11.094 ±(99.9%) 0.050 ms/op
# Warmup Iteration   2: 4.246 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.806 ±(99.9%) 0.009 ms/op
Iteration   1: 3.718 ±(99.9%) 0.004 ms/op
Iteration   2: 3.711 ±(99.9%) 0.007 ms/op
Iteration   3: 3.787 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.739 ±(99.9%) 0.765 ms/op [Average]
  (min, avg, max) = (3.711, 3.739, 3.787), stdev = 0.042
  CI (99.9%): [2.974, 4.503] (assumes normal distribution)


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
# Warmup Iteration   1: 12.954 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.674 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.258 ±(99.9%) 0.007 ms/op
Iteration   1: 3.993 ±(99.9%) 0.010 ms/op
Iteration   2: 3.956 ±(99.9%) 0.011 ms/op
Iteration   3: 3.854 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.934 ±(99.9%) 1.310 ms/op [Average]
  (min, avg, max) = (3.854, 3.934, 3.993), stdev = 0.072
  CI (99.9%): [2.624, 5.245] (assumes normal distribution)


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
# Warmup Iteration   1: 14.542 ±(99.9%) 0.064 ms/op
# Warmup Iteration   2: 5.442 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.706 ±(99.9%) 0.010 ms/op
Iteration   1: 4.691 ±(99.9%) 0.011 ms/op
Iteration   2: 4.645 ±(99.9%) 0.016 ms/op
Iteration   3: 4.621 ±(99.9%) 0.015 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.652 ±(99.9%) 0.648 ms/op [Average]
  (min, avg, max) = (4.621, 4.652, 4.691), stdev = 0.036
  CI (99.9%): [4.004, 5.300] (assumes normal distribution)


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
# Warmup Iteration   1: 12.352 ±(99.9%) 0.194 ms/op
# Warmup Iteration   2: 5.138 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.380 ±(99.9%) 0.017 ms/op
Iteration   1: 4.056 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.866 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.390 ms/op
                 createUser·p0.99:   7.487 ms/op
                 createUser·p0.999:  23.331 ms/op
                 createUser·p0.9999: 27.918 ms/op
                 createUser·p1.00:   28.508 ms/op

Iteration   2: 3.933 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.634 ms/op
                 createUser·p0.50:   3.740 ms/op
                 createUser·p0.90:   4.473 ms/op
                 createUser·p0.95:   4.825 ms/op
                 createUser·p0.99:   7.266 ms/op
                 createUser·p0.999:  26.006 ms/op
                 createUser·p0.9999: 29.581 ms/op
                 createUser·p1.00:   31.162 ms/op

Iteration   3: 4.026 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.130 ms/op
                 createUser·p0.50:   3.830 ms/op
                 createUser·p0.90:   4.727 ms/op
                 createUser·p0.95:   5.054 ms/op
                 createUser·p0.99:   6.499 ms/op
                 createUser·p0.999:  25.330 ms/op
                 createUser·p0.9999: 33.131 ms/op
                 createUser·p1.00:   33.489 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239644
  mean =      4.004 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 499 
    [ 2.500,  5.000) = 226514 
    [ 5.000,  7.500) = 10540 
    [ 7.500, 10.000) = 1220 
    [10.000, 12.500) = 444 
    [12.500, 15.000) = 79 
    [15.000, 17.500) = 58 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 70 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 56 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.130 ms/op
     p(50.0000) =      3.817 ms/op
     p(90.0000) =      4.653 ms/op
     p(95.0000) =      5.038 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     24.052 ms/op
     p(99.9900) =     32.343 ms/op
     p(99.9990) =     33.325 ms/op
     p(99.9999) =     33.489 ms/op
    p(100.0000) =     33.489 ms/op


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
# Warmup Iteration   1: 12.078 ±(99.9%) 0.181 ms/op
# Warmup Iteration   2: 4.047 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 4.110 ±(99.9%) 0.012 ms/op
Iteration   1: 3.839 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.989 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.817 ms/op
                 existUser·p0.99:   6.791 ms/op
                 existUser·p0.999:  23.896 ms/op
                 existUser·p0.9999: 26.564 ms/op
                 existUser·p1.00:   30.048 ms/op

Iteration   2: 3.891 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.735 ms/op
                 existUser·p0.50:   3.748 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   4.997 ms/op
                 existUser·p0.99:   6.775 ms/op
                 existUser·p0.999:  14.844 ms/op
                 existUser·p0.9999: 27.052 ms/op
                 existUser·p1.00:   27.558 ms/op

Iteration   3: 3.830 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.253 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.424 ms/op
                 existUser·p0.95:   4.923 ms/op
                 existUser·p0.99:   6.316 ms/op
                 existUser·p0.999:  14.500 ms/op
                 existUser·p0.9999: 30.365 ms/op
                 existUser·p1.00:   31.752 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 249096
  mean =      3.853 ±(99.9%) 0.006 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 234 
    [ 2.500,  5.000) = 237801 
    [ 5.000,  7.500) = 9625 
    [ 7.500, 10.000) = 918 
    [10.000, 12.500) = 179 
    [12.500, 15.000) = 82 
    [15.000, 17.500) = 33 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 61 
    [25.000, 27.500) = 99 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 20 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.253 ms/op
     p(50.0000) =      3.731 ms/op
     p(90.0000) =      4.432 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      6.627 ms/op
     p(99.9000) =     15.106 ms/op
     p(99.9900) =     29.655 ms/op
     p(99.9990) =     31.097 ms/op
     p(99.9999) =     31.752 ms/op
    p(100.0000) =     31.752 ms/op


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
# Warmup Iteration   1: 12.824 ±(99.9%) 0.202 ms/op
# Warmup Iteration   2: 4.581 ±(99.9%) 0.023 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.011 ms/op
Iteration   1: 4.000 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.620 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.694 ms/op
                 getUser·p0.95:   5.399 ms/op
                 getUser·p0.99:   7.930 ms/op
                 getUser·p0.999:  22.320 ms/op
                 getUser·p0.9999: 28.312 ms/op
                 getUser·p1.00:   32.735 ms/op

Iteration   2: 3.843 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   1.649 ms/op
                 getUser·p0.50:   3.740 ms/op
                 getUser·p0.90:   4.182 ms/op
                 getUser·p0.95:   4.424 ms/op
                 getUser·p0.99:   6.622 ms/op
                 getUser·p0.999:  14.172 ms/op
                 getUser·p0.9999: 26.903 ms/op
                 getUser·p1.00:   27.689 ms/op

Iteration   3: 3.822 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.077 ms/op
                 getUser·p0.50:   3.715 ms/op
                 getUser·p0.90:   4.153 ms/op
                 getUser·p0.95:   4.391 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  25.384 ms/op
                 getUser·p0.9999: 28.377 ms/op
                 getUser·p1.00:   29.458 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 246867
  mean =      3.887 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 87 
    [ 2.500,  5.000) = 237202 
    [ 5.000,  7.500) = 7656 
    [ 7.500, 10.000) = 1131 
    [10.000, 12.500) = 388 
    [12.500, 15.000) = 88 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 41 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 141 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 2 
    [32.500, 35.000) = 1 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.620 ms/op
     p(50.0000) =      3.744 ms/op
     p(90.0000) =      4.309 ms/op
     p(95.0000) =      4.760 ms/op
     p(99.0000) =      7.160 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     28.049 ms/op
     p(99.9990) =     31.588 ms/op
     p(99.9999) =     32.735 ms/op
    p(100.0000) =     32.735 ms/op


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
# Warmup Iteration   1: 14.578 ±(99.9%) 0.217 ms/op
# Warmup Iteration   2: 5.300 ±(99.9%) 0.025 ms/op
# Warmup Iteration   3: 4.833 ±(99.9%) 0.017 ms/op
Iteration   1: 4.575 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.370 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   4.989 ms/op
                 listUser·p0.95:   5.300 ms/op
                 listUser·p0.99:   8.364 ms/op
                 listUser·p0.999:  23.101 ms/op
                 listUser·p0.9999: 26.116 ms/op
                 listUser·p1.00:   27.066 ms/op

Iteration   2: 4.627 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.954 ms/op
                 listUser·p0.50:   4.448 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  17.291 ms/op
                 listUser·p0.9999: 21.040 ms/op
                 listUser·p1.00:   21.496 ms/op

Iteration   3: 4.611 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.700 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   5.046 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.233 ms/op
                 listUser·p0.999:  17.770 ms/op
                 listUser·p0.9999: 21.365 ms/op
                 listUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 208402
  mean =      4.604 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 27 
    [ 2.500,  5.000) = 184450 
    [ 5.000,  7.500) = 19662 
    [ 7.500, 10.000) = 3201 
    [10.000, 12.500) = 562 
    [12.500, 15.000) = 63 
    [15.000, 17.500) = 172 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 63 
    [22.500, 25.000) = 76 
    [25.000, 27.500) = 26 

  Percentiles, ms/op:
      p(0.0000) =      1.370 ms/op
     p(50.0000) =      4.424 ms/op
     p(90.0000) =      5.063 ms/op
     p(95.0000) =      5.538 ms/op
     p(99.0000) =      8.471 ms/op
     p(99.9000) =     18.796 ms/op
     p(99.9900) =     25.411 ms/op
     p(99.9990) =     26.441 ms/op
     p(99.9999) =     27.066 ms/op
    p(100.0000) =     27.066 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.832 ± 5.987  ops/ms
ClientPb.existUser                       thrpt       3   8.405 ± 1.361  ops/ms
ClientPb.getUser                         thrpt       3   8.263 ± 2.943  ops/ms
ClientPb.listUser                        thrpt       3   6.786 ± 1.567  ops/ms
ClientPb.createUser                       avgt       3   3.893 ± 1.498   ms/op
ClientPb.existUser                        avgt       3   3.739 ± 0.765   ms/op
ClientPb.getUser                          avgt       3   3.934 ± 1.310   ms/op
ClientPb.listUser                         avgt       3   4.652 ± 0.648   ms/op
ClientPb.createUser                     sample  239644   4.004 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.130           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.817           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.653           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.038           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.225           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.052           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.343           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.489           ms/op
ClientPb.existUser                      sample  249096   3.853 ± 0.006   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.253           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.731           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.432           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.99      sample           6.627           ms/op
ClientPb.existUser:existUser·p0.999     sample          15.106           ms/op
ClientPb.existUser:existUser·p0.9999    sample          29.655           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.752           ms/op
ClientPb.getUser                        sample  246867   3.887 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.620           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.744           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.309           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.760           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.160           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.217           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.049           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.735           ms/op
ClientPb.listUser                       sample  208402   4.604 ± 0.007   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.370           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.424           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.063           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.538           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.471           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.796           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.411           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.066           ms/op
