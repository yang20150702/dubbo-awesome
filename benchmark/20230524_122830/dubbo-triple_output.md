# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.111 ops/ms
# Warmup Iteration   2: 2.310 ops/ms
# Warmup Iteration   3: 4.983 ops/ms
Iteration   1: 5.405 ops/ms
Iteration   2: 5.559 ops/ms
Iteration   3: 5.691 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.552 ±(99.9%) 2.607 ops/ms [Average]
  (min, avg, max) = (5.405, 5.552, 5.691), stdev = 0.143
  CI (99.9%): [2.945, 8.158] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:16
# Fork: 1 of 1
# Warmup Iteration   1: 1.658 ops/ms
# Warmup Iteration   2: 4.607 ops/ms
# Warmup Iteration   3: 5.941 ops/ms
Iteration   1: 5.903 ops/ms
Iteration   2: 5.949 ops/ms
Iteration   3: 5.967 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.940 ±(99.9%) 0.602 ops/ms [Average]
  (min, avg, max) = (5.903, 5.940, 5.967), stdev = 0.033
  CI (99.9%): [5.338, 6.542] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:09
# Fork: 1 of 1
# Warmup Iteration   1: 1.438 ops/ms
# Warmup Iteration   2: 4.074 ops/ms
# Warmup Iteration   3: 5.598 ops/ms
Iteration   1: 5.754 ops/ms
Iteration   2: 5.817 ops/ms
Iteration   3: 5.781 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.784 ±(99.9%) 0.575 ops/ms [Average]
  (min, avg, max) = (5.754, 5.784, 5.817), stdev = 0.032
  CI (99.9%): [5.208, 6.359] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:10:02
# Fork: 1 of 1
# Warmup Iteration   1: 1.317 ops/ms
# Warmup Iteration   2: 3.922 ops/ms
# Warmup Iteration   3: 4.790 ops/ms
Iteration   1: 4.765 ops/ms
Iteration   2: 4.951 ops/ms
Iteration   3: 4.974 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.897 ±(99.9%) 2.092 ops/ms [Average]
  (min, avg, max) = (4.765, 4.897, 4.974), stdev = 0.115
  CI (99.9%): [2.805, 6.989] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:55
# Fork: 1 of 1
# Warmup Iteration   1: 19.939 ±(99.9%) 0.154 ms/op
# Warmup Iteration   2: 7.115 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.647 ±(99.9%) 0.013 ms/op
Iteration   1: 5.262 ±(99.9%) 0.025 ms/op
Iteration   2: 5.445 ±(99.9%) 0.015 ms/op
Iteration   3: 5.370 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.359 ±(99.9%) 1.686 ms/op [Average]
  (min, avg, max) = (5.262, 5.359, 5.445), stdev = 0.092
  CI (99.9%): [3.673, 7.045] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 18.310 ±(99.9%) 0.088 ms/op
# Warmup Iteration   2: 6.392 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 5.381 ±(99.9%) 0.011 ms/op
Iteration   1: 5.262 ±(99.9%) 0.008 ms/op
Iteration   2: 5.064 ±(99.9%) 0.012 ms/op
Iteration   3: 5.171 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.166 ±(99.9%) 1.806 ms/op [Average]
  (min, avg, max) = (5.064, 5.166, 5.262), stdev = 0.099
  CI (99.9%): [3.360, 6.971] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:40
# Fork: 1 of 1
# Warmup Iteration   1: 19.772 ±(99.9%) 0.097 ms/op
# Warmup Iteration   2: 6.240 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 5.365 ±(99.9%) 0.014 ms/op
Iteration   1: 5.447 ±(99.9%) 0.015 ms/op
Iteration   2: 5.472 ±(99.9%) 0.012 ms/op
Iteration   3: 5.272 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.397 ±(99.9%) 1.988 ms/op [Average]
  (min, avg, max) = (5.272, 5.397, 5.472), stdev = 0.109
  CI (99.9%): [3.409, 7.385] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 21.338 ±(99.9%) 0.102 ms/op
# Warmup Iteration   2: 7.575 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 6.316 ±(99.9%) 0.014 ms/op
Iteration   1: 6.480 ±(99.9%) 0.013 ms/op
Iteration   2: 6.082 ±(99.9%) 0.016 ms/op
Iteration   3: 6.152 ±(99.9%) 0.014 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.238 ±(99.9%) 3.871 ms/op [Average]
  (min, avg, max) = (6.082, 6.238, 6.480), stdev = 0.212
  CI (99.9%): [2.367, 10.109] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:26
# Fork: 1 of 1
# Warmup Iteration   1: 17.183 ±(99.9%) 0.278 ms/op
# Warmup Iteration   2: 6.844 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 6.089 ±(99.9%) 0.031 ms/op
Iteration   1: 5.537 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   5.259 ms/op
                 createUser·p0.90:   6.562 ms/op
                 createUser·p0.95:   7.586 ms/op
                 createUser·p0.99:   11.034 ms/op
                 createUser·p0.999:  25.695 ms/op
                 createUser·p0.9999: 27.900 ms/op
                 createUser·p1.00:   29.491 ms/op

Iteration   2: 5.733 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.535 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   6.947 ms/op
                 createUser·p0.95:   8.118 ms/op
                 createUser·p0.99:   12.403 ms/op
                 createUser·p0.999:  26.984 ms/op
                 createUser·p0.9999: 32.613 ms/op
                 createUser·p1.00:   33.522 ms/op

Iteration   3: 5.500 ±(99.9%) 0.020 ms/op
                 createUser·p0.00:   0.881 ms/op
                 createUser·p0.50:   5.202 ms/op
                 createUser·p0.90:   6.775 ms/op
                 createUser·p0.95:   7.922 ms/op
                 createUser·p0.99:   10.457 ms/op
                 createUser·p0.999:  28.204 ms/op
                 createUser·p0.9999: 32.016 ms/op
                 createUser·p1.00:   32.965 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 171876
  mean =      5.588 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 53220 
    [ 5.000,  7.500) = 108104 
    [ 7.500, 10.000) = 7803 
    [10.000, 12.500) = 1587 
    [12.500, 15.000) = 520 
    [15.000, 17.500) = 214 
    [17.500, 20.000) = 153 
    [20.000, 22.500) = 45 
    [22.500, 25.000) = 26 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 62 
    [32.500, 35.000) = 12 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.881 ms/op
     p(50.0000) =      5.267 ms/op
     p(90.0000) =      6.775 ms/op
     p(95.0000) =      7.922 ms/op
     p(99.0000) =     11.161 ms/op
     p(99.9000) =     26.186 ms/op
     p(99.9900) =     32.336 ms/op
     p(99.9990) =     33.498 ms/op
     p(99.9999) =     33.522 ms/op
    p(100.0000) =     33.522 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 16.750 ±(99.9%) 0.261 ms/op
# Warmup Iteration   2: 6.207 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 4.954 ±(99.9%) 0.016 ms/op
Iteration   1: 5.083 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.216 ms/op
                 existUser·p0.50:   4.719 ms/op
                 existUser·p0.90:   6.537 ms/op
                 existUser·p0.95:   7.782 ms/op
                 existUser·p0.99:   10.682 ms/op
                 existUser·p0.999:  22.654 ms/op
                 existUser·p0.9999: 32.585 ms/op
                 existUser·p1.00:   33.456 ms/op

Iteration   2: 4.948 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   2.007 ms/op
                 existUser·p0.50:   4.702 ms/op
                 existUser·p0.90:   5.988 ms/op
                 existUser·p0.95:   6.898 ms/op
                 existUser·p0.99:   9.388 ms/op
                 existUser·p0.999:  25.600 ms/op
                 existUser·p0.9999: 29.000 ms/op
                 existUser·p1.00:   30.605 ms/op

Iteration   3: 5.102 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   4.809 ms/op
                 existUser·p0.90:   6.201 ms/op
                 existUser·p0.95:   7.283 ms/op
                 existUser·p0.99:   10.306 ms/op
                 existUser·p0.999:  27.698 ms/op
                 existUser·p0.9999: 31.824 ms/op
                 existUser·p1.00:   32.571 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 190269
  mean =      5.043 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 34 
    [ 2.500,  5.000) = 124699 
    [ 5.000,  7.500) = 56698 
    [ 7.500, 10.000) = 6800 
    [10.000, 12.500) = 1319 
    [12.500, 15.000) = 401 
    [15.000, 17.500) = 89 
    [17.500, 20.000) = 15 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 81 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.007 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      6.218 ms/op
     p(95.0000) =      7.381 ms/op
     p(99.0000) =     10.158 ms/op
     p(99.9000) =     23.855 ms/op
     p(99.9900) =     31.748 ms/op
     p(99.9990) =     33.190 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:13
# Fork: 1 of 1
# Warmup Iteration   1: 17.685 ±(99.9%) 0.299 ms/op
# Warmup Iteration   2: 6.535 ±(99.9%) 0.040 ms/op
# Warmup Iteration   3: 5.779 ±(99.9%) 0.024 ms/op
Iteration   1: 5.808 ±(99.9%) 0.025 ms/op
                 getUser·p0.00:   2.052 ms/op
                 getUser·p0.50:   5.358 ms/op
                 getUser·p0.90:   7.168 ms/op
                 getUser·p0.95:   9.306 ms/op
                 getUser·p0.99:   13.304 ms/op
                 getUser·p0.999:  24.696 ms/op
                 getUser·p0.9999: 29.720 ms/op
                 getUser·p1.00:   30.343 ms/op

Iteration   2: 5.439 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.851 ms/op
                 getUser·p0.50:   5.177 ms/op
                 getUser·p0.90:   6.472 ms/op
                 getUser·p0.95:   7.242 ms/op
                 getUser·p0.99:   10.467 ms/op
                 getUser·p0.999:  25.696 ms/op
                 getUser·p0.9999: 28.880 ms/op
                 getUser·p1.00:   31.490 ms/op

Iteration   3: 5.274 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.825 ms/op
                 getUser·p0.50:   5.054 ms/op
                 getUser·p0.90:   6.201 ms/op
                 getUser·p0.95:   6.922 ms/op
                 getUser·p0.99:   9.667 ms/op
                 getUser·p0.999:  28.751 ms/op
                 getUser·p0.9999: 31.587 ms/op
                 getUser·p1.00:   31.883 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 174428
  mean =      5.498 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 12 
    [ 2.500,  5.000) = 67648 
    [ 5.000,  7.500) = 97438 
    [ 7.500, 10.000) = 6160 
    [10.000, 12.500) = 1981 
    [12.500, 15.000) = 605 
    [15.000, 17.500) = 252 
    [17.500, 20.000) = 134 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 11 
    [25.000, 27.500) = 57 
    [27.500, 30.000) = 80 
    [30.000, 32.500) = 44 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.825 ms/op
     p(50.0000) =      5.177 ms/op
     p(90.0000) =      6.578 ms/op
     p(95.0000) =      7.635 ms/op
     p(99.0000) =     11.387 ms/op
     p(99.9000) =     25.657 ms/op
     p(99.9900) =     30.755 ms/op
     p(99.9990) =     31.859 ms/op
     p(99.9999) =     31.883 ms/op
    p(100.0000) =     31.883 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_372, OpenJDK 64-Bit Server VM, 25.372-b07
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.372-7/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.111 ±(99.9%) 0.293 ms/op
# Warmup Iteration   2: 7.495 ±(99.9%) 0.049 ms/op
# Warmup Iteration   3: 6.511 ±(99.9%) 0.026 ms/op
Iteration   1: 6.276 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   2.978 ms/op
                 listUser·p0.50:   5.890 ms/op
                 listUser·p0.90:   7.602 ms/op
                 listUser·p0.95:   8.536 ms/op
                 listUser·p0.99:   12.220 ms/op
                 listUser·p0.999:  29.360 ms/op
                 listUser·p0.9999: 31.768 ms/op
                 listUser·p1.00:   32.408 ms/op

Iteration   2: 6.235 ±(99.9%) 0.023 ms/op
                 listUser·p0.00:   2.290 ms/op
                 listUser·p0.50:   5.931 ms/op
                 listUser·p0.90:   7.307 ms/op
                 listUser·p0.95:   8.258 ms/op
                 listUser·p0.99:   11.666 ms/op
                 listUser·p0.999:  28.475 ms/op
                 listUser·p0.9999: 31.617 ms/op
                 listUser·p1.00:   32.375 ms/op

Iteration   3: 6.456 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   1.933 ms/op
                 listUser·p0.50:   6.070 ms/op
                 listUser·p0.90:   7.832 ms/op
                 listUser·p0.95:   8.651 ms/op
                 listUser·p0.99:   12.578 ms/op
                 listUser·p0.999:  24.871 ms/op
                 listUser·p0.9999: 32.902 ms/op
                 listUser·p1.00:   35.324 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 151839
  mean =      6.321 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 7035 
    [ 5.000,  7.500) = 128355 
    [ 7.500, 10.000) = 12853 
    [10.000, 12.500) = 2275 
    [12.500, 15.000) = 634 
    [15.000, 17.500) = 269 
    [17.500, 20.000) = 82 
    [20.000, 22.500) = 27 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 75 
    [27.500, 30.000) = 102 
    [30.000, 32.500) = 75 
    [32.500, 35.000) = 5 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.933 ms/op
     p(50.0000) =      5.956 ms/op
     p(90.0000) =      7.594 ms/op
     p(95.0000) =      8.503 ms/op
     p(99.0000) =     12.173 ms/op
     p(99.9000) =     28.344 ms/op
     p(99.9900) =     32.029 ms/op
     p(99.9990) =     34.848 ms/op
     p(99.9999) =     35.324 ms/op
    p(100.0000) =     35.324 ms/op


# Run complete. Total time: 00:13:20

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.552 ± 2.607  ops/ms
ClientPb.existUser                       thrpt       3   5.940 ± 0.602  ops/ms
ClientPb.getUser                         thrpt       3   5.784 ± 0.575  ops/ms
ClientPb.listUser                        thrpt       3   4.897 ± 2.092  ops/ms
ClientPb.createUser                       avgt       3   5.359 ± 1.686   ms/op
ClientPb.existUser                        avgt       3   5.166 ± 1.806   ms/op
ClientPb.getUser                          avgt       3   5.397 ± 1.988   ms/op
ClientPb.listUser                         avgt       3   6.238 ± 3.871   ms/op
ClientPb.createUser                     sample  171876   5.588 ± 0.012   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.881           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.775           ms/op
ClientPb.createUser:createUser·p0.95    sample           7.922           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.161           ms/op
ClientPb.createUser:createUser·p0.999   sample          26.186           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.336           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.522           ms/op
ClientPb.existUser                      sample  190269   5.043 ± 0.011   ms/op
ClientPb.existUser:existUser·p0.00      sample           2.007           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.735           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.218           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.381           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.158           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.855           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.748           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.456           ms/op
ClientPb.getUser                        sample  174428   5.498 ± 0.012   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.825           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.177           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.578           ms/op
ClientPb.getUser:getUser·p0.95          sample           7.635           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.387           ms/op
ClientPb.getUser:getUser·p0.999         sample          25.657           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.755           ms/op
ClientPb.getUser:getUser·p1.00          sample          31.883           ms/op
ClientPb.listUser                       sample  151839   6.321 ± 0.014   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.933           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.956           ms/op
ClientPb.listUser:listUser·p0.90        sample           7.594           ms/op
ClientPb.listUser:listUser·p0.95        sample           8.503           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.173           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.344           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.029           ms/op
ClientPb.listUser:listUser·p1.00        sample          35.324           ms/op
