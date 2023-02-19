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
# Warmup Iteration   1: 1.092 ops/ms
# Warmup Iteration   2: 2.492 ops/ms
# Warmup Iteration   3: 4.965 ops/ms
Iteration   1: 5.033 ops/ms
Iteration   2: 5.421 ops/ms
Iteration   3: 5.360 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.272 ±(99.9%) 3.812 ops/ms [Average]
  (min, avg, max) = (5.033, 5.272, 5.421), stdev = 0.209
  CI (99.9%): [1.460, 9.083] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.582 ops/ms
# Warmup Iteration   2: 4.782 ops/ms
# Warmup Iteration   3: 5.542 ops/ms
Iteration   1: 5.691 ops/ms
Iteration   2: 5.611 ops/ms
Iteration   3: 5.663 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.655 ±(99.9%) 0.741 ops/ms [Average]
  (min, avg, max) = (5.611, 5.655, 5.691), stdev = 0.041
  CI (99.9%): [4.914, 6.396] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.529 ops/ms
# Warmup Iteration   2: 4.020 ops/ms
# Warmup Iteration   3: 5.190 ops/ms
Iteration   1: 5.206 ops/ms
Iteration   2: 5.360 ops/ms
Iteration   3: 5.155 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.240 ±(99.9%) 1.945 ops/ms [Average]
  (min, avg, max) = (5.155, 5.240, 5.360), stdev = 0.107
  CI (99.9%): [3.295, 7.186] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.413 ops/ms
# Warmup Iteration   2: 3.271 ops/ms
# Warmup Iteration   3: 4.219 ops/ms
Iteration   1: 4.500 ops/ms
Iteration   2: 4.755 ops/ms
Iteration   3: 4.834 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.696 ±(99.9%) 3.193 ops/ms [Average]
  (min, avg, max) = (4.500, 4.696, 4.834), stdev = 0.175
  CI (99.9%): [1.504, 7.889] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 20.035 ±(99.9%) 0.131 ms/op
# Warmup Iteration   2: 7.409 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.086 ±(99.9%) 0.007 ms/op
Iteration   1: 5.850 ±(99.9%) 0.016 ms/op
Iteration   2: 5.887 ±(99.9%) 0.012 ms/op
Iteration   3: 5.927 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.888 ±(99.9%) 0.699 ms/op [Average]
  (min, avg, max) = (5.850, 5.888, 5.927), stdev = 0.038
  CI (99.9%): [5.189, 6.587] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 17.094 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.655 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.816 ±(99.9%) 0.008 ms/op
Iteration   1: 5.600 ±(99.9%) 0.013 ms/op
Iteration   2: 5.734 ±(99.9%) 0.009 ms/op
Iteration   3: 5.440 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.591 ±(99.9%) 2.681 ms/op [Average]
  (min, avg, max) = (5.440, 5.591, 5.734), stdev = 0.147
  CI (99.9%): [2.911, 8.272] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 19.296 ±(99.9%) 0.086 ms/op
# Warmup Iteration   2: 7.276 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.137 ±(99.9%) 0.014 ms/op
Iteration   1: 6.042 ±(99.9%) 0.012 ms/op
Iteration   2: 5.974 ±(99.9%) 0.010 ms/op
Iteration   3: 5.915 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.977 ±(99.9%) 1.162 ms/op [Average]
  (min, avg, max) = (5.915, 5.977, 6.042), stdev = 0.064
  CI (99.9%): [4.815, 7.138] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 20.739 ±(99.9%) 0.098 ms/op
# Warmup Iteration   2: 8.170 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.876 ±(99.9%) 0.012 ms/op
Iteration   1: 6.928 ±(99.9%) 0.015 ms/op
Iteration   2: 6.817 ±(99.9%) 0.011 ms/op
Iteration   3: 6.816 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.854 ±(99.9%) 1.171 ms/op [Average]
  (min, avg, max) = (6.816, 6.854, 6.928), stdev = 0.064
  CI (99.9%): [5.683, 8.025] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 17.660 ±(99.9%) 0.320 ms/op
# Warmup Iteration   2: 7.522 ±(99.9%) 0.052 ms/op
# Warmup Iteration   3: 6.776 ±(99.9%) 0.038 ms/op
Iteration   1: 5.941 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.499 ms/op
                 createUser·p0.50:   5.620 ms/op
                 createUser·p0.90:   7.528 ms/op
                 createUser·p0.95:   8.667 ms/op
                 createUser·p0.99:   11.436 ms/op
                 createUser·p0.999:  17.451 ms/op
                 createUser·p0.9999: 31.874 ms/op
                 createUser·p1.00:   35.389 ms/op

Iteration   2: 5.718 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.335 ms/op
                 createUser·p0.50:   5.464 ms/op
                 createUser·p0.90:   7.078 ms/op
                 createUser·p0.95:   7.750 ms/op
                 createUser·p0.99:   9.961 ms/op
                 createUser·p0.999:  27.001 ms/op
                 createUser·p0.9999: 30.252 ms/op
                 createUser·p1.00:   30.540 ms/op

Iteration   3: 5.816 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   5.472 ms/op
                 createUser·p0.90:   7.258 ms/op
                 createUser·p0.95:   8.339 ms/op
                 createUser·p0.99:   11.108 ms/op
                 createUser·p0.999:  27.984 ms/op
                 createUser·p0.9999: 31.703 ms/op
                 createUser·p1.00:   32.342 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164754
  mean =      5.824 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14 
    [ 2.500,  5.000) = 42589 
    [ 5.000,  7.500) = 108516 
    [ 7.500, 10.000) = 10910 
    [10.000, 12.500) = 1830 
    [12.500, 15.000) = 462 
    [15.000, 17.500) = 193 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 55 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 2 

  Percentiles, ms/op:
      p(0.0000) =      2.335 ms/op
     p(50.0000) =      5.513 ms/op
     p(90.0000) =      7.283 ms/op
     p(95.0000) =      8.200 ms/op
     p(99.0000) =     10.945 ms/op
     p(99.9000) =     19.284 ms/op
     p(99.9900) =     31.248 ms/op
     p(99.9990) =     35.262 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 17.937 ±(99.9%) 0.326 ms/op
# Warmup Iteration   2: 6.599 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 5.663 ±(99.9%) 0.022 ms/op
Iteration   1: 5.796 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   2.241 ms/op
                 existUser·p0.50:   5.480 ms/op
                 existUser·p0.90:   7.365 ms/op
                 existUser·p0.95:   8.438 ms/op
                 existUser·p0.99:   10.813 ms/op
                 existUser·p0.999:  14.595 ms/op
                 existUser·p0.9999: 41.581 ms/op
                 existUser·p1.00:   42.926 ms/op

Iteration   2: 5.849 ±(99.9%) 0.024 ms/op
                 existUser·p0.00:   1.436 ms/op
                 existUser·p0.50:   5.480 ms/op
                 existUser·p0.90:   7.397 ms/op
                 existUser·p0.95:   8.487 ms/op
                 existUser·p0.99:   12.288 ms/op
                 existUser·p0.999:  24.511 ms/op
                 existUser·p0.9999: 31.475 ms/op
                 existUser·p1.00:   32.702 ms/op

Iteration   3: 5.741 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.392 ms/op
                 existUser·p0.50:   5.374 ms/op
                 existUser·p0.90:   7.340 ms/op
                 existUser·p0.95:   8.339 ms/op
                 existUser·p0.99:   11.043 ms/op
                 existUser·p0.999:  15.647 ms/op
                 existUser·p0.9999: 29.829 ms/op
                 existUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 165537
  mean =      5.795 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 46348 
    [ 5.000, 10.000) = 116097 
    [10.000, 15.000) = 2701 
    [15.000, 20.000) = 231 
    [20.000, 25.000) = 44 
    [25.000, 30.000) = 66 
    [30.000, 35.000) = 18 
    [35.000, 40.000) = 15 
    [40.000, 45.000) = 17 

  Percentiles, ms/op:
      p(0.0000) =      1.436 ms/op
     p(50.0000) =      5.448 ms/op
     p(90.0000) =      7.373 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.272 ms/op
     p(99.9000) =     19.578 ms/op
     p(99.9900) =     40.130 ms/op
     p(99.9990) =     42.840 ms/op
     p(99.9999) =     42.926 ms/op
    p(100.0000) =     42.926 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 18.060 ±(99.9%) 0.350 ms/op
# Warmup Iteration   2: 7.182 ±(99.9%) 0.048 ms/op
# Warmup Iteration   3: 5.934 ±(99.9%) 0.023 ms/op
Iteration   1: 5.539 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.346 ms/op
                 getUser·p0.50:   5.284 ms/op
                 getUser·p0.90:   6.709 ms/op
                 getUser·p0.95:   7.586 ms/op
                 getUser·p0.99:   10.519 ms/op
                 getUser·p0.999:  15.346 ms/op
                 getUser·p0.9999: 24.642 ms/op
                 getUser·p1.00:   25.166 ms/op

Iteration   2: 5.758 ±(99.9%) 0.021 ms/op
                 getUser·p0.00:   2.163 ms/op
                 getUser·p0.50:   5.464 ms/op
                 getUser·p0.90:   7.102 ms/op
                 getUser·p0.95:   7.889 ms/op
                 getUser·p0.99:   10.928 ms/op
                 getUser·p0.999:  26.935 ms/op
                 getUser·p0.9999: 31.632 ms/op
                 getUser·p1.00:   33.391 ms/op

Iteration   3: 5.878 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   0.529 ms/op
                 getUser·p0.50:   5.521 ms/op
                 getUser·p0.90:   7.373 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   11.190 ms/op
                 getUser·p0.999:  28.997 ms/op
                 getUser·p0.9999: 31.479 ms/op
                 getUser·p1.00:   32.506 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 167793
  mean =      5.722 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 45124 
    [ 5.000,  7.500) = 110724 
    [ 7.500, 10.000) = 9189 
    [10.000, 12.500) = 1927 
    [12.500, 15.000) = 427 
    [15.000, 17.500) = 165 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 39 
    [25.000, 27.500) = 20 
    [27.500, 30.000) = 45 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 2 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.529 ms/op
     p(50.0000) =      5.423 ms/op
     p(90.0000) =      7.062 ms/op
     p(95.0000) =      8.028 ms/op
     p(99.0000) =     10.895 ms/op
     p(99.9000) =     22.566 ms/op
     p(99.9900) =     31.290 ms/op
     p(99.9990) =     32.791 ms/op
     p(99.9999) =     33.391 ms/op
    p(100.0000) =     33.391 ms/op


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
# Warmup Iteration   1: 21.338 ±(99.9%) 0.364 ms/op
# Warmup Iteration   2: 8.545 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 7.161 ±(99.9%) 0.030 ms/op
Iteration   1: 6.948 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.855 ms/op
                 listUser·p0.50:   6.603 ms/op
                 listUser·p0.90:   8.503 ms/op
                 listUser·p0.95:   9.896 ms/op
                 listUser·p0.99:   12.452 ms/op
                 listUser·p0.999:  28.279 ms/op
                 listUser·p0.9999: 31.927 ms/op
                 listUser·p1.00:   33.620 ms/op

Iteration   2: 7.105 ±(99.9%) 0.033 ms/op
                 listUser·p0.00:   2.879 ms/op
                 listUser·p0.50:   6.545 ms/op
                 listUser·p0.90:   9.470 ms/op
                 listUser·p0.95:   10.666 ms/op
                 listUser·p0.99:   13.959 ms/op
                 listUser·p0.999:  32.634 ms/op
                 listUser·p0.9999: 38.895 ms/op
                 listUser·p1.00:   40.894 ms/op

Iteration   3: 7.045 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.613 ms/op
                 listUser·p0.50:   6.660 ms/op
                 listUser·p0.90:   8.585 ms/op
                 listUser·p0.95:   9.896 ms/op
                 listUser·p0.99:   13.206 ms/op
                 listUser·p0.999:  29.478 ms/op
                 listUser·p0.9999: 43.312 ms/op
                 listUser·p1.00:   43.909 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 136597
  mean =      7.032 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 2285 
    [ 5.000, 10.000) = 126520 
    [10.000, 15.000) = 7090 
    [15.000, 20.000) = 380 
    [20.000, 25.000) = 48 
    [25.000, 30.000) = 118 
    [30.000, 35.000) = 92 
    [35.000, 40.000) = 54 
    [40.000, 45.000) = 10 

  Percentiles, ms/op:
      p(0.0000) =      2.613 ms/op
     p(50.0000) =      6.611 ms/op
     p(90.0000) =      8.798 ms/op
     p(95.0000) =     10.256 ms/op
     p(99.0000) =     13.173 ms/op
     p(99.9000) =     31.130 ms/op
     p(99.9900) =     39.606 ms/op
     p(99.9990) =     43.885 ms/op
     p(99.9999) =     43.909 ms/op
    p(100.0000) =     43.909 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.272 ± 3.812  ops/ms
ClientPb.existUser                       thrpt       3   5.655 ± 0.741  ops/ms
ClientPb.getUser                         thrpt       3   5.240 ± 1.945  ops/ms
ClientPb.listUser                        thrpt       3   4.696 ± 3.193  ops/ms
ClientPb.createUser                       avgt       3   5.888 ± 0.699   ms/op
ClientPb.existUser                        avgt       3   5.591 ± 2.681   ms/op
ClientPb.getUser                          avgt       3   5.977 ± 1.162   ms/op
ClientPb.listUser                         avgt       3   6.854 ± 1.171   ms/op
ClientPb.createUser                     sample  164754   5.824 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.335           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.513           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.283           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.200           ms/op
ClientPb.createUser:createUser·p0.99    sample          10.945           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.284           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.248           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.389           ms/op
ClientPb.existUser                      sample  165537   5.795 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.436           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.448           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.373           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.405           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.272           ms/op
ClientPb.existUser:existUser·p0.999     sample          19.578           ms/op
ClientPb.existUser:existUser·p0.9999    sample          40.130           ms/op
ClientPb.existUser:existUser·p1.00      sample          42.926           ms/op
ClientPb.getUser                        sample  167793   5.722 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.529           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.423           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.062           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.028           ms/op
ClientPb.getUser:getUser·p0.99          sample          10.895           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.566           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.290           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.391           ms/op
ClientPb.listUser                       sample  136597   7.032 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.613           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.611           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.798           ms/op
ClientPb.listUser:listUser·p0.95        sample          10.256           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.173           ms/op
ClientPb.listUser:listUser·p0.999       sample          31.130           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.606           ms/op
ClientPb.listUser:listUser·p1.00        sample          43.909           ms/op
