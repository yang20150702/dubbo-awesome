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
# Warmup Iteration   1: 1.596 ops/ms
# Warmup Iteration   2: 3.548 ops/ms
# Warmup Iteration   3: 7.323 ops/ms
Iteration   1: 7.116 ops/ms
Iteration   2: 7.715 ops/ms
Iteration   3: 7.854 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.562 ±(99.9%) 7.151 ops/ms [Average]
  (min, avg, max) = (7.116, 7.562, 7.854), stdev = 0.392
  CI (99.9%): [0.410, 14.713] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:13
# Fork: 1 of 1
# Warmup Iteration   1: 1.967 ops/ms
# Warmup Iteration   2: 6.667 ops/ms
# Warmup Iteration   3: 8.099 ops/ms
Iteration   1: 8.201 ops/ms
Iteration   2: 8.366 ops/ms
Iteration   3: 7.952 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.173 ±(99.9%) 3.808 ops/ms [Average]
  (min, avg, max) = (7.952, 8.173, 8.366), stdev = 0.209
  CI (99.9%): [4.365, 11.981] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:06
# Fork: 1 of 1
# Warmup Iteration   1: 2.323 ops/ms
# Warmup Iteration   2: 6.993 ops/ms
# Warmup Iteration   3: 7.716 ops/ms
Iteration   1: 7.602 ops/ms
Iteration   2: 7.866 ops/ms
Iteration   3: 8.080 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.849 ±(99.9%) 4.367 ops/ms [Average]
  (min, avg, max) = (7.602, 7.849, 8.080), stdev = 0.239
  CI (99.9%): [3.482, 12.216] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:59
# Fork: 1 of 1
# Warmup Iteration   1: 2.002 ops/ms
# Warmup Iteration   2: 5.287 ops/ms
# Warmup Iteration   3: 6.491 ops/ms
Iteration   1: 6.867 ops/ms
Iteration   2: 6.652 ops/ms
Iteration   3: 6.839 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.786 ±(99.9%) 2.137 ops/ms [Average]
  (min, avg, max) = (6.652, 6.786, 6.867), stdev = 0.117
  CI (99.9%): [4.649, 8.923] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:52
# Fork: 1 of 1
# Warmup Iteration   1: 14.915 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 4.859 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.206 ±(99.9%) 0.011 ms/op
Iteration   1: 4.086 ±(99.9%) 0.005 ms/op
Iteration   2: 4.041 ±(99.9%) 0.009 ms/op
Iteration   3: 4.106 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.078 ±(99.9%) 0.612 ms/op [Average]
  (min, avg, max) = (4.041, 4.078, 4.106), stdev = 0.034
  CI (99.9%): [3.466, 4.690] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:45
# Fork: 1 of 1
# Warmup Iteration   1: 12.618 ±(99.9%) 0.077 ms/op
# Warmup Iteration   2: 4.585 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.868 ±(99.9%) 0.009 ms/op
Iteration   1: 4.059 ±(99.9%) 0.008 ms/op
Iteration   2: 3.976 ±(99.9%) 0.008 ms/op
Iteration   3: 3.798 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.944 ±(99.9%) 2.433 ms/op [Average]
  (min, avg, max) = (3.798, 3.944, 4.059), stdev = 0.133
  CI (99.9%): [1.510, 6.377] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 13.779 ±(99.9%) 0.047 ms/op
# Warmup Iteration   2: 4.759 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.294 ±(99.9%) 0.003 ms/op
Iteration   1: 4.257 ±(99.9%) 0.005 ms/op
Iteration   2: 4.018 ±(99.9%) 0.009 ms/op
Iteration   3: 4.049 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  4.108 ±(99.9%) 2.370 ms/op [Average]
  (min, avg, max) = (4.018, 4.108, 4.257), stdev = 0.130
  CI (99.9%): [1.738, 6.478] (assumes normal distribution)


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
# Warmup Iteration   1: 14.464 ±(99.9%) 0.056 ms/op
# Warmup Iteration   2: 5.915 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.136 ±(99.9%) 0.009 ms/op
Iteration   1: 4.821 ±(99.9%) 0.012 ms/op
Iteration   2: 4.802 ±(99.9%) 0.011 ms/op
Iteration   3: 4.732 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.785 ±(99.9%) 0.854 ms/op [Average]
  (min, avg, max) = (4.732, 4.785, 4.821), stdev = 0.047
  CI (99.9%): [3.931, 5.640] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 14.019 ±(99.9%) 0.213 ms/op
# Warmup Iteration   2: 5.736 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 4.769 ±(99.9%) 0.023 ms/op
Iteration   1: 4.170 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.981 ms/op
                 createUser·p0.90:   4.932 ms/op
                 createUser·p0.95:   5.947 ms/op
                 createUser·p0.99:   8.102 ms/op
                 createUser·p0.999:  11.652 ms/op
                 createUser·p0.9999: 25.383 ms/op
                 createUser·p1.00:   27.754 ms/op

Iteration   2: 4.182 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.257 ms/op
                 createUser·p0.50:   3.994 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.431 ms/op
                 createUser·p0.99:   8.007 ms/op
                 createUser·p0.999:  25.511 ms/op
                 createUser·p0.9999: 29.699 ms/op
                 createUser·p1.00:   29.884 ms/op

Iteration   3: 4.019 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.393 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   4.981 ms/op
                 createUser·p0.99:   7.225 ms/op
                 createUser·p0.999:  19.053 ms/op
                 createUser·p0.9999: 35.261 ms/op
                 createUser·p1.00:   35.914 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 232816
  mean =      4.122 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 206 
    [ 2.500,  5.000) = 215677 
    [ 5.000,  7.500) = 14095 
    [ 7.500, 10.000) = 2262 
    [10.000, 12.500) = 261 
    [12.500, 15.000) = 45 
    [15.000, 17.500) = 14 
    [17.500, 20.000) = 32 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 29 
    [32.500, 35.000) = 25 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.257 ms/op
     p(50.0000) =      3.940 ms/op
     p(90.0000) =      4.768 ms/op
     p(95.0000) =      5.407 ms/op
     p(99.0000) =      7.815 ms/op
     p(99.9000) =     19.366 ms/op
     p(99.9900) =     33.630 ms/op
     p(99.9990) =     35.914 ms/op
     p(99.9999) =     35.914 ms/op
    p(100.0000) =     35.914 ms/op


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
# Warmup Iteration   1: 13.865 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 4.507 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 3.877 ±(99.9%) 0.010 ms/op
Iteration   1: 3.981 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.850 ms/op
                 existUser·p0.90:   4.596 ms/op
                 existUser·p0.95:   5.226 ms/op
                 existUser·p0.99:   7.339 ms/op
                 existUser·p0.999:  11.813 ms/op
                 existUser·p0.9999: 25.885 ms/op
                 existUser·p1.00:   26.870 ms/op

Iteration   2: 3.937 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.715 ms/op
                 existUser·p0.90:   4.481 ms/op
                 existUser·p0.95:   5.112 ms/op
                 existUser·p0.99:   7.209 ms/op
                 existUser·p0.999:  25.919 ms/op
                 existUser·p0.9999: 28.803 ms/op
                 existUser·p1.00:   29.327 ms/op

Iteration   3: 3.983 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.536 ms/op
                 existUser·p0.50:   3.846 ms/op
                 existUser·p0.90:   4.432 ms/op
                 existUser·p0.95:   5.128 ms/op
                 existUser·p0.99:   7.669 ms/op
                 existUser·p0.999:  13.566 ms/op
                 existUser·p0.9999: 29.027 ms/op
                 existUser·p1.00:   31.392 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 241821
  mean =      3.967 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 271 
    [ 2.500,  5.000) = 227696 
    [ 5.000,  7.500) = 11557 
    [ 7.500, 10.000) = 1629 
    [10.000, 12.500) = 332 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 5 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 2 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 118 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 5 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.506 ms/op
     p(95.0000) =      5.161 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     14.631 ms/op
     p(99.9900) =     28.705 ms/op
     p(99.9990) =     31.003 ms/op
     p(99.9999) =     31.392 ms/op
    p(100.0000) =     31.392 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 13.922 ±(99.9%) 0.197 ms/op
# Warmup Iteration   2: 5.290 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.430 ±(99.9%) 0.015 ms/op
Iteration   1: 4.442 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   1.522 ms/op
                 getUser·p0.50:   4.202 ms/op
                 getUser·p0.90:   5.317 ms/op
                 getUser·p0.95:   6.201 ms/op
                 getUser·p0.99:   8.331 ms/op
                 getUser·p0.999:  18.972 ms/op
                 getUser·p0.9999: 27.053 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 4.166 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.154 ms/op
                 getUser·p0.50:   4.039 ms/op
                 getUser·p0.90:   4.743 ms/op
                 getUser·p0.95:   5.325 ms/op
                 getUser·p0.99:   7.578 ms/op
                 getUser·p0.999:  25.919 ms/op
                 getUser·p0.9999: 30.147 ms/op
                 getUser·p1.00:   30.802 ms/op

Iteration   3: 4.098 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.933 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.473 ms/op
                 getUser·p0.95:   4.866 ms/op
                 getUser·p0.99:   7.938 ms/op
                 getUser·p0.999:  14.370 ms/op
                 getUser·p0.9999: 32.316 ms/op
                 getUser·p1.00:   32.997 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 226782
  mean =      4.230 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 35 
    [ 2.500,  5.000) = 207304 
    [ 5.000,  7.500) = 16460 
    [ 7.500, 10.000) = 2129 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 98 
    [15.000, 17.500) = 25 
    [17.500, 20.000) = 36 
    [20.000, 22.500) = 1 
    [22.500, 25.000) = 40 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 69 
    [30.000, 32.500) = 49 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.522 ms/op
     p(50.0000) =      4.063 ms/op
     p(90.0000) =      4.891 ms/op
     p(95.0000) =      5.569 ms/op
     p(99.0000) =      8.012 ms/op
     p(99.9000) =     19.161 ms/op
     p(99.9900) =     31.785 ms/op
     p(99.9990) =     32.879 ms/op
     p(99.9999) =     32.997 ms/op
    p(100.0000) =     32.997 ms/op


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
# Warmup Iteration   1: 15.219 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.895 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.853 ±(99.9%) 0.016 ms/op
Iteration   1: 5.014 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   0.729 ms/op
                 listUser·p0.50:   4.735 ms/op
                 listUser·p0.90:   5.775 ms/op
                 listUser·p0.95:   7.168 ms/op
                 listUser·p0.99:   9.699 ms/op
                 listUser·p0.999:  23.050 ms/op
                 listUser·p0.9999: 26.062 ms/op
                 listUser·p1.00:   26.903 ms/op

Iteration   2: 4.845 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.806 ms/op
                 listUser·p0.50:   4.530 ms/op
                 listUser·p0.90:   5.554 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   8.847 ms/op
                 listUser·p0.999:  17.269 ms/op
                 listUser·p0.9999: 23.049 ms/op
                 listUser·p1.00:   23.626 ms/op

Iteration   3: 4.860 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.724 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.677 ms/op
                 listUser·p0.95:   6.447 ms/op
                 listUser·p0.99:   8.798 ms/op
                 listUser·p0.999:  17.439 ms/op
                 listUser·p0.9999: 19.481 ms/op
                 listUser·p1.00:   20.120 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 195600
  mean =      4.905 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 29 
    [ 2.500,  5.000) = 143999 
    [ 5.000,  7.500) = 45221 
    [ 7.500, 10.000) = 5070 
    [10.000, 12.500) = 678 
    [12.500, 15.000) = 189 
    [15.000, 17.500) = 150 
    [17.500, 20.000) = 110 
    [20.000, 22.500) = 71 
    [22.500, 25.000) = 63 
    [25.000, 27.500) = 20 

  Percentiles, ms/op:
      p(0.0000) =      0.729 ms/op
     p(50.0000) =      4.637 ms/op
     p(90.0000) =      5.644 ms/op
     p(95.0000) =      6.627 ms/op
     p(99.0000) =      9.257 ms/op
     p(99.9000) =     18.678 ms/op
     p(99.9900) =     25.068 ms/op
     p(99.9990) =     26.903 ms/op
     p(99.9999) =     26.903 ms/op
    p(100.0000) =     26.903 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.562 ± 7.151  ops/ms
ClientPb.existUser                       thrpt       3   8.173 ± 3.808  ops/ms
ClientPb.getUser                         thrpt       3   7.849 ± 4.367  ops/ms
ClientPb.listUser                        thrpt       3   6.786 ± 2.137  ops/ms
ClientPb.createUser                       avgt       3   4.078 ± 0.612   ms/op
ClientPb.existUser                        avgt       3   3.944 ± 2.433   ms/op
ClientPb.getUser                          avgt       3   4.108 ± 2.370   ms/op
ClientPb.listUser                         avgt       3   4.785 ± 0.854   ms/op
ClientPb.createUser                     sample  232816   4.122 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.257           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.940           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.768           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.407           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.815           ms/op
ClientPb.createUser:createUser·p0.999   sample          19.366           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.630           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  241821   3.967 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.446           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.805           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.506           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.161           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.447           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.631           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.705           ms/op
ClientPb.existUser:existUser·p1.00      sample          31.392           ms/op
ClientPb.getUser                        sample  226782   4.230 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.522           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.063           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.569           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.012           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.161           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.785           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.997           ms/op
ClientPb.listUser                       sample  195600   4.905 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.729           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.637           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.644           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.627           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.257           ms/op
ClientPb.listUser:listUser·p0.999       sample          18.678           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.068           ms/op
ClientPb.listUser:listUser·p1.00        sample          26.903           ms/op
