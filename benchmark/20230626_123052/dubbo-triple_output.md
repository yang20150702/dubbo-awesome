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
# Warmup Iteration   1: 1.505 ops/ms
# Warmup Iteration   2: 2.955 ops/ms
# Warmup Iteration   3: 6.771 ops/ms
Iteration   1: 7.388 ops/ms
Iteration   2: 7.879 ops/ms
Iteration   3: 7.755 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.674 ±(99.9%) 4.656 ops/ms [Average]
  (min, avg, max) = (7.388, 7.674, 7.879), stdev = 0.255
  CI (99.9%): [3.018, 12.330] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:12
# Fork: 1 of 1
# Warmup Iteration   1: 2.330 ops/ms
# Warmup Iteration   2: 6.917 ops/ms
# Warmup Iteration   3: 7.940 ops/ms
Iteration   1: 8.374 ops/ms
Iteration   2: 8.469 ops/ms
Iteration   3: 8.086 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.309 ±(99.9%) 3.634 ops/ms [Average]
  (min, avg, max) = (8.086, 8.309, 8.469), stdev = 0.199
  CI (99.9%): [4.676, 11.943] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:05
# Fork: 1 of 1
# Warmup Iteration   1: 2.186 ops/ms
# Warmup Iteration   2: 6.495 ops/ms
# Warmup Iteration   3: 7.783 ops/ms
Iteration   1: 7.743 ops/ms
Iteration   2: 7.880 ops/ms
Iteration   3: 7.890 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.838 ±(99.9%) 1.505 ops/ms [Average]
  (min, avg, max) = (7.743, 7.838, 7.890), stdev = 0.082
  CI (99.9%): [6.333, 9.343] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:58
# Fork: 1 of 1
# Warmup Iteration   1: 1.871 ops/ms
# Warmup Iteration   2: 5.453 ops/ms
# Warmup Iteration   3: 6.458 ops/ms
Iteration   1: 6.768 ops/ms
Iteration   2: 6.943 ops/ms
Iteration   3: 6.912 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.874 ±(99.9%) 1.703 ops/ms [Average]
  (min, avg, max) = (6.768, 6.874, 6.943), stdev = 0.093
  CI (99.9%): [5.171, 8.578] (assumes normal distribution)


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
# Warmup Iteration   1: 13.876 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 5.009 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.196 ±(99.9%) 0.010 ms/op
Iteration   1: 4.051 ±(99.9%) 0.011 ms/op
Iteration   2: 4.131 ±(99.9%) 0.009 ms/op
Iteration   3: 3.975 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.053 ±(99.9%) 1.426 ms/op [Average]
  (min, avg, max) = (3.975, 4.053, 4.131), stdev = 0.078
  CI (99.9%): [2.627, 5.478] (assumes normal distribution)


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
# Warmup Iteration   1: 13.089 ±(99.9%) 0.048 ms/op
# Warmup Iteration   2: 4.262 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.916 ±(99.9%) 0.006 ms/op
Iteration   1: 3.781 ±(99.9%) 0.010 ms/op
Iteration   2: 3.820 ±(99.9%) 0.008 ms/op
Iteration   3: 3.990 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.864 ±(99.9%) 2.024 ms/op [Average]
  (min, avg, max) = (3.781, 3.864, 3.990), stdev = 0.111
  CI (99.9%): [1.839, 5.888] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:39
# Fork: 1 of 1
# Warmup Iteration   1: 11.339 ±(99.9%) 0.051 ms/op
# Warmup Iteration   2: 4.883 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.181 ±(99.9%) 0.005 ms/op
Iteration   1: 3.918 ±(99.9%) 0.011 ms/op
Iteration   2: 4.053 ±(99.9%) 0.005 ms/op
Iteration   3: 4.012 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.994 ±(99.9%) 1.256 ms/op [Average]
  (min, avg, max) = (3.918, 3.994, 4.053), stdev = 0.069
  CI (99.9%): [2.738, 5.250] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 13.959 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.425 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 4.900 ±(99.9%) 0.005 ms/op
Iteration   1: 4.802 ±(99.9%) 0.006 ms/op
Iteration   2: 4.627 ±(99.9%) 0.014 ms/op
Iteration   3: 4.669 ±(99.9%) 0.013 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.699 ±(99.9%) 1.665 ms/op [Average]
  (min, avg, max) = (4.627, 4.699, 4.802), stdev = 0.091
  CI (99.9%): [3.034, 6.365] (assumes normal distribution)


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
# Warmup Iteration   1: 12.845 ±(99.9%) 0.196 ms/op
# Warmup Iteration   2: 4.952 ±(99.9%) 0.026 ms/op
# Warmup Iteration   3: 4.319 ±(99.9%) 0.017 ms/op
Iteration   1: 3.883 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.538 ms/op
                 createUser·p0.50:   3.772 ms/op
                 createUser·p0.90:   4.235 ms/op
                 createUser·p0.95:   4.596 ms/op
                 createUser·p0.99:   6.860 ms/op
                 createUser·p0.999:  23.790 ms/op
                 createUser·p0.9999: 30.877 ms/op
                 createUser·p1.00:   31.949 ms/op

Iteration   2: 4.080 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.716 ms/op
                 createUser·p0.50:   3.850 ms/op
                 createUser·p0.90:   4.768 ms/op
                 createUser·p0.95:   5.439 ms/op
                 createUser·p0.99:   8.315 ms/op
                 createUser·p0.999:  25.467 ms/op
                 createUser·p0.9999: 27.787 ms/op
                 createUser·p1.00:   28.312 ms/op

Iteration   3: 3.977 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.063 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   4.522 ms/op
                 createUser·p0.95:   4.940 ms/op
                 createUser·p0.99:   7.111 ms/op
                 createUser·p0.999:  22.547 ms/op
                 createUser·p0.9999: 31.587 ms/op
                 createUser·p1.00:   33.194 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 241287
  mean =      3.978 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 353 
    [ 2.500,  5.000) = 229308 
    [ 5.000,  7.500) = 9264 
    [ 7.500, 10.000) = 1377 
    [10.000, 12.500) = 462 
    [12.500, 15.000) = 169 
    [15.000, 17.500) = 28 
    [17.500, 20.000) = 10 
    [20.000, 22.500) = 29 
    [22.500, 25.000) = 68 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 72 
    [30.000, 32.500) = 61 
    [32.500, 35.000) = 7 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.063 ms/op
     p(50.0000) =      3.797 ms/op
     p(90.0000) =      4.530 ms/op
     p(95.0000) =      4.973 ms/op
     p(99.0000) =      7.447 ms/op
     p(99.9000) =     23.911 ms/op
     p(99.9900) =     30.900 ms/op
     p(99.9990) =     33.148 ms/op
     p(99.9999) =     33.194 ms/op
    p(100.0000) =     33.194 ms/op


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
# Warmup Iteration   1: 11.072 ±(99.9%) 0.165 ms/op
# Warmup Iteration   2: 4.189 ±(99.9%) 0.015 ms/op
# Warmup Iteration   3: 3.891 ±(99.9%) 0.011 ms/op
Iteration   1: 4.011 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.446 ms/op
                 existUser·p0.50:   3.752 ms/op
                 existUser·p0.90:   4.776 ms/op
                 existUser·p0.95:   5.439 ms/op
                 existUser·p0.99:   7.421 ms/op
                 existUser·p0.999:  11.326 ms/op
                 existUser·p0.9999: 34.144 ms/op
                 existUser·p1.00:   34.537 ms/op

Iteration   2: 3.807 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.505 ms/op
                 existUser·p0.50:   3.756 ms/op
                 existUser·p0.90:   4.076 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.562 ms/op
                 existUser·p0.999:  13.337 ms/op
                 existUser·p0.9999: 27.512 ms/op
                 existUser·p1.00:   28.836 ms/op

Iteration   3: 3.820 ±(99.9%) 0.015 ms/op
                 existUser·p0.00:   1.528 ms/op
                 existUser·p0.50:   3.777 ms/op
                 existUser·p0.90:   3.985 ms/op
                 existUser·p0.95:   4.424 ms/op
                 existUser·p0.99:   6.930 ms/op
                 existUser·p0.999:  27.689 ms/op
                 existUser·p0.9999: 47.948 ms/op
                 existUser·p1.00:   49.152 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247459
  mean =      3.877 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 236060 
    [ 5.000, 10.000) = 10735 
    [10.000, 15.000) = 435 
    [15.000, 20.000) = 5 
    [20.000, 25.000) = 0 
    [25.000, 30.000) = 154 
    [30.000, 35.000) = 38 
    [35.000, 40.000) = 0 
    [40.000, 45.000) = 4 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.383 ms/op
     p(95.0000) =      4.915 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     13.469 ms/op
     p(99.9900) =     46.892 ms/op
     p(99.9990) =     48.990 ms/op
     p(99.9999) =     49.152 ms/op
    p(100.0000) =     49.152 ms/op


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
# Warmup Iteration   1: 12.940 ±(99.9%) 0.185 ms/op
# Warmup Iteration   2: 4.501 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 4.157 ±(99.9%) 0.013 ms/op
Iteration   1: 4.150 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.896 ms/op
                 getUser·p0.50:   3.944 ms/op
                 getUser·p0.90:   4.825 ms/op
                 getUser·p0.95:   5.276 ms/op
                 getUser·p0.99:   7.958 ms/op
                 getUser·p0.999:  23.326 ms/op
                 getUser·p0.9999: 27.342 ms/op
                 getUser·p1.00:   27.918 ms/op

Iteration   2: 4.011 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   2.257 ms/op
                 getUser·p0.50:   3.916 ms/op
                 getUser·p0.90:   4.342 ms/op
                 getUser·p0.95:   4.555 ms/op
                 getUser·p0.99:   7.070 ms/op
                 getUser·p0.999:  16.595 ms/op
                 getUser·p0.9999: 26.411 ms/op
                 getUser·p1.00:   27.525 ms/op

Iteration   3: 4.079 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   2.150 ms/op
                 getUser·p0.50:   3.887 ms/op
                 getUser·p0.90:   4.645 ms/op
                 getUser·p0.95:   5.718 ms/op
                 getUser·p0.99:   7.086 ms/op
                 getUser·p0.999:  26.759 ms/op
                 getUser·p0.9999: 29.245 ms/op
                 getUser·p1.00:   29.655 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 235321
  mean =      4.079 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 30 
    [ 2.500,  5.000) = 222127 
    [ 5.000,  7.500) = 11027 
    [ 7.500, 10.000) = 1374 
    [10.000, 12.500) = 366 
    [12.500, 15.000) = 65 
    [15.000, 17.500) = 36 
    [17.500, 20.000) = 8 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 101 
    [25.000, 27.500) = 111 

  Percentiles, ms/op:
      p(0.0000) =      1.896 ms/op
     p(50.0000) =      3.920 ms/op
     p(90.0000) =      4.620 ms/op
     p(95.0000) =      5.112 ms/op
     p(99.0000) =      7.340 ms/op
     p(99.9000) =     23.419 ms/op
     p(99.9900) =     28.556 ms/op
     p(99.9990) =     29.588 ms/op
     p(99.9999) =     29.655 ms/op
    p(100.0000) =     29.655 ms/op


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
# Warmup Iteration   1: 13.966 ±(99.9%) 0.207 ms/op
# Warmup Iteration   2: 5.541 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.927 ±(99.9%) 0.017 ms/op
Iteration   1: 4.841 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   1.571 ms/op
                 listUser·p0.50:   4.571 ms/op
                 listUser·p0.90:   5.448 ms/op
                 listUser·p0.95:   6.316 ms/op
                 listUser·p0.99:   8.946 ms/op
                 listUser·p0.999:  26.667 ms/op
                 listUser·p0.9999: 38.666 ms/op
                 listUser·p1.00:   39.387 ms/op

Iteration   2: 4.677 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.675 ms/op
                 listUser·p0.50:   4.538 ms/op
                 listUser·p0.90:   5.054 ms/op
                 listUser·p0.95:   5.390 ms/op
                 listUser·p0.99:   8.585 ms/op
                 listUser·p0.999:  18.387 ms/op
                 listUser·p0.9999: 21.730 ms/op
                 listUser·p1.00:   22.577 ms/op

Iteration   3: 4.829 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   1.608 ms/op
                 listUser·p0.50:   4.612 ms/op
                 listUser·p0.90:   5.431 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   9.421 ms/op
                 listUser·p0.999:  17.263 ms/op
                 listUser·p0.9999: 19.739 ms/op
                 listUser·p1.00:   20.185 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 200648
  mean =      4.781 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 166962 
    [ 5.000,  7.500) = 27998 
    [ 7.500, 10.000) = 4387 
    [10.000, 12.500) = 629 
    [12.500, 15.000) = 228 
    [15.000, 17.500) = 121 
    [17.500, 20.000) = 119 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 11 
    [30.000, 32.500) = 0 
    [32.500, 35.000) = 11 
    [35.000, 37.500) = 10 

  Percentiles, ms/op:
      p(0.0000) =      1.571 ms/op
     p(50.0000) =      4.579 ms/op
     p(90.0000) =      5.317 ms/op
     p(95.0000) =      5.898 ms/op
     p(99.0000) =      8.978 ms/op
     p(99.9000) =     19.597 ms/op
     p(99.9900) =     35.062 ms/op
     p(99.9990) =     39.322 ms/op
     p(99.9999) =     39.387 ms/op
    p(100.0000) =     39.387 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.674 ± 4.656  ops/ms
ClientPb.existUser                       thrpt       3   8.309 ± 3.634  ops/ms
ClientPb.getUser                         thrpt       3   7.838 ± 1.505  ops/ms
ClientPb.listUser                        thrpt       3   6.874 ± 1.703  ops/ms
ClientPb.createUser                       avgt       3   4.053 ± 1.426   ms/op
ClientPb.existUser                        avgt       3   3.864 ± 2.024   ms/op
ClientPb.getUser                          avgt       3   3.994 ± 1.256   ms/op
ClientPb.listUser                         avgt       3   4.699 ± 1.665   ms/op
ClientPb.createUser                     sample  241287   3.978 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.063           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.797           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.530           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.973           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.447           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.911           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.900           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.194           ms/op
ClientPb.existUser                      sample  247459   3.877 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.446           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.383           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.915           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.062           ms/op
ClientPb.existUser:existUser·p0.999     sample          13.469           ms/op
ClientPb.existUser:existUser·p0.9999    sample          46.892           ms/op
ClientPb.existUser:existUser·p1.00      sample          49.152           ms/op
ClientPb.getUser                        sample  235321   4.079 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.896           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.920           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.620           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.112           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.340           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.419           ms/op
ClientPb.getUser:getUser·p0.9999        sample          28.556           ms/op
ClientPb.getUser:getUser·p1.00          sample          29.655           ms/op
ClientPb.listUser                       sample  200648   4.781 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.571           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.579           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.317           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.898           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.978           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.597           ms/op
ClientPb.listUser:listUser·p0.9999      sample          35.062           ms/op
ClientPb.listUser:listUser·p1.00        sample          39.387           ms/op
