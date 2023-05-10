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
# Warmup Iteration   1: 1.725 ops/ms
# Warmup Iteration   2: 3.800 ops/ms
# Warmup Iteration   3: 6.707 ops/ms
Iteration   1: 7.270 ops/ms
Iteration   2: 8.086 ops/ms
Iteration   3: 8.201 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.852 ±(99.9%) 9.260 ops/ms [Average]
  (min, avg, max) = (7.270, 7.852, 8.201), stdev = 0.508
  CI (99.9%): [≈ 0, 17.112] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:02
# Fork: 1 of 1
# Warmup Iteration   1: 2.048 ops/ms
# Warmup Iteration   2: 6.390 ops/ms
# Warmup Iteration   3: 7.645 ops/ms
Iteration   1: 8.249 ops/ms
Iteration   2: 8.021 ops/ms
Iteration   3: 7.656 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  7.975 ±(99.9%) 5.458 ops/ms [Average]
  (min, avg, max) = (7.656, 7.975, 8.249), stdev = 0.299
  CI (99.9%): [2.518, 13.433] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:01
# Fork: 1 of 1
# Warmup Iteration   1: 1.990 ops/ms
# Warmup Iteration   2: 5.626 ops/ms
# Warmup Iteration   3: 7.313 ops/ms
Iteration   1: 7.524 ops/ms
Iteration   2: 8.045 ops/ms
Iteration   3: 7.744 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.771 ±(99.9%) 4.775 ops/ms [Average]
  (min, avg, max) = (7.524, 7.771, 8.045), stdev = 0.262
  CI (99.9%): [2.996, 12.547] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:56
# Fork: 1 of 1
# Warmup Iteration   1: 2.009 ops/ms
# Warmup Iteration   2: 5.250 ops/ms
# Warmup Iteration   3: 6.117 ops/ms
Iteration   1: 6.636 ops/ms
Iteration   2: 7.001 ops/ms
Iteration   3: 6.860 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.832 ±(99.9%) 3.355 ops/ms [Average]
  (min, avg, max) = (6.636, 6.832, 7.001), stdev = 0.184
  CI (99.9%): [3.477, 10.188] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 14.725 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 5.316 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.236 ±(99.9%) 0.006 ms/op
Iteration   1: 3.971 ±(99.9%) 0.012 ms/op
Iteration   2: 3.951 ±(99.9%) 0.009 ms/op
Iteration   3: 4.121 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.014 ±(99.9%) 1.690 ms/op [Average]
  (min, avg, max) = (3.951, 4.014, 4.121), stdev = 0.093
  CI (99.9%): [2.324, 5.705] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 13.448 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 4.418 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 4.166 ±(99.9%) 0.004 ms/op
Iteration   1: 4.167 ±(99.9%) 0.008 ms/op
Iteration   2: 4.103 ±(99.9%) 0.008 ms/op
Iteration   3: 4.123 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.131 ±(99.9%) 0.590 ms/op [Average]
  (min, avg, max) = (4.103, 4.131, 4.167), stdev = 0.032
  CI (99.9%): [3.541, 4.721] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 11.553 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 4.896 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.369 ±(99.9%) 0.009 ms/op
Iteration   1: 4.112 ±(99.9%) 0.010 ms/op
Iteration   2: 3.858 ±(99.9%) 0.007 ms/op
Iteration   3: 3.837 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.936 ±(99.9%) 2.785 ms/op [Average]
  (min, avg, max) = (3.837, 3.936, 4.112), stdev = 0.153
  CI (99.9%): [1.151, 6.721] (assumes normal distribution)


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
# Warmup Iteration   1: 13.782 ±(99.9%) 0.070 ms/op
# Warmup Iteration   2: 5.570 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.786 ±(99.9%) 0.012 ms/op
Iteration   1: 4.955 ±(99.9%) 0.009 ms/op
Iteration   2: 4.596 ±(99.9%) 0.013 ms/op
Iteration   3: 4.711 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.754 ±(99.9%) 3.344 ms/op [Average]
  (min, avg, max) = (4.596, 4.754, 4.955), stdev = 0.183
  CI (99.9%): [1.410, 8.098] (assumes normal distribution)


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
# Warmup Iteration   1: 14.029 ±(99.9%) 0.188 ms/op
# Warmup Iteration   2: 5.679 ±(99.9%) 0.036 ms/op
# Warmup Iteration   3: 4.454 ±(99.9%) 0.021 ms/op
Iteration   1: 4.168 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.731 ms/op
                 createUser·p0.50:   3.973 ms/op
                 createUser·p0.90:   4.833 ms/op
                 createUser·p0.95:   5.669 ms/op
                 createUser·p0.99:   8.241 ms/op
                 createUser·p0.999:  11.452 ms/op
                 createUser·p0.9999: 35.301 ms/op
                 createUser·p1.00:   35.914 ms/op

Iteration   2: 4.222 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   1.831 ms/op
                 createUser·p0.50:   4.010 ms/op
                 createUser·p0.90:   4.940 ms/op
                 createUser·p0.95:   5.579 ms/op
                 createUser·p0.99:   7.611 ms/op
                 createUser·p0.999:  25.566 ms/op
                 createUser·p0.9999: 29.360 ms/op
                 createUser·p1.00:   30.933 ms/op

Iteration   3: 4.372 ±(99.9%) 0.015 ms/op
                 createUser·p0.00:   0.421 ms/op
                 createUser·p0.50:   4.108 ms/op
                 createUser·p0.90:   5.259 ms/op
                 createUser·p0.95:   6.308 ms/op
                 createUser·p0.99:   8.192 ms/op
                 createUser·p0.999:  17.924 ms/op
                 createUser·p0.9999: 33.446 ms/op
                 createUser·p1.00:   34.013 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 225645
  mean =      4.252 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 339 
    [ 2.500,  5.000) = 202363 
    [ 5.000,  7.500) = 19614 
    [ 7.500, 10.000) = 2600 
    [10.000, 12.500) = 403 
    [12.500, 15.000) = 48 
    [15.000, 17.500) = 3 
    [17.500, 20.000) = 22 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 27 
    [25.000, 27.500) = 79 
    [27.500, 30.000) = 88 
    [30.000, 32.500) = 18 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 13 

  Percentiles, ms/op:
      p(0.0000) =      0.421 ms/op
     p(50.0000) =      4.043 ms/op
     p(90.0000) =      5.014 ms/op
     p(95.0000) =      5.830 ms/op
     p(99.0000) =      8.086 ms/op
     p(99.9000) =     24.784 ms/op
     p(99.9900) =     33.391 ms/op
     p(99.9990) =     35.667 ms/op
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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 13.385 ±(99.9%) 0.174 ms/op
# Warmup Iteration   2: 4.822 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.348 ±(99.9%) 0.014 ms/op
Iteration   1: 4.036 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.864 ms/op
                 existUser·p0.50:   3.699 ms/op
                 existUser·p0.90:   5.063 ms/op
                 existUser·p0.95:   5.669 ms/op
                 existUser·p0.99:   8.004 ms/op
                 existUser·p0.999:  12.551 ms/op
                 existUser·p0.9999: 25.103 ms/op
                 existUser·p1.00:   26.509 ms/op

Iteration   2: 3.848 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.710 ms/op
                 existUser·p0.50:   3.674 ms/op
                 existUser·p0.90:   4.276 ms/op
                 existUser·p0.95:   4.743 ms/op
                 existUser·p0.99:   7.519 ms/op
                 existUser·p0.999:  13.156 ms/op
                 existUser·p0.9999: 24.294 ms/op
                 existUser·p1.00:   24.838 ms/op

Iteration   3: 4.181 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.638 ms/op
                 existUser·p0.50:   3.977 ms/op
                 existUser·p0.90:   4.964 ms/op
                 existUser·p0.95:   5.636 ms/op
                 existUser·p0.99:   7.815 ms/op
                 existUser·p0.999:  25.854 ms/op
                 existUser·p0.9999: 29.361 ms/op
                 existUser·p1.00:   30.081 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 238587
  mean =      4.017 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 203 
    [ 2.500,  5.000) = 219013 
    [ 5.000,  7.500) = 16556 
    [ 7.500, 10.000) = 2192 
    [10.000, 12.500) = 314 
    [12.500, 15.000) = 73 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 97 
    [25.000, 27.500) = 51 
    [27.500, 30.000) = 44 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.638 ms/op
     p(50.0000) =      3.760 ms/op
     p(90.0000) =      4.784 ms/op
     p(95.0000) =      5.456 ms/op
     p(99.0000) =      7.750 ms/op
     p(99.9000) =     14.598 ms/op
     p(99.9900) =     28.457 ms/op
     p(99.9990) =     29.856 ms/op
     p(99.9999) =     30.081 ms/op
    p(100.0000) =     30.081 ms/op


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
# Warmup Iteration   1: 13.059 ±(99.9%) 0.199 ms/op
# Warmup Iteration   2: 5.003 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 4.423 ±(99.9%) 0.019 ms/op
Iteration   1: 4.402 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.663 ms/op
                 getUser·p0.50:   4.084 ms/op
                 getUser·p0.90:   5.505 ms/op
                 getUser·p0.95:   6.644 ms/op
                 getUser·p0.99:   9.322 ms/op
                 getUser·p0.999:  17.706 ms/op
                 getUser·p0.9999: 27.347 ms/op
                 getUser·p1.00:   28.770 ms/op

Iteration   2: 4.112 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.419 ms/op
                 getUser·p0.50:   3.903 ms/op
                 getUser·p0.90:   4.678 ms/op
                 getUser·p0.95:   5.915 ms/op
                 getUser·p0.99:   8.086 ms/op
                 getUser·p0.999:  14.867 ms/op
                 getUser·p0.9999: 27.218 ms/op
                 getUser·p1.00:   27.984 ms/op

Iteration   3: 4.066 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.892 ms/op
                 getUser·p0.50:   3.924 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.885 ms/op
                 getUser·p0.99:   6.936 ms/op
                 getUser·p0.999:  27.951 ms/op
                 getUser·p0.9999: 31.626 ms/op
                 getUser·p1.00:   32.014 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 229173
  mean =      4.188 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 76 
    [ 2.500,  5.000) = 208854 
    [ 5.000,  7.500) = 16567 
    [ 7.500, 10.000) = 2761 
    [10.000, 12.500) = 470 
    [12.500, 15.000) = 143 
    [15.000, 17.500) = 61 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 32 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 75 
    [30.000, 32.500) = 31 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.419 ms/op
     p(50.0000) =      3.957 ms/op
     p(90.0000) =      4.874 ms/op
     p(95.0000) =      5.997 ms/op
     p(99.0000) =      8.258 ms/op
     p(99.9000) =     17.787 ms/op
     p(99.9900) =     30.411 ms/op
     p(99.9990) =     31.818 ms/op
     p(99.9999) =     32.014 ms/op
    p(100.0000) =     32.014 ms/op


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
# Warmup Iteration   1: 15.114 ±(99.9%) 0.222 ms/op
# Warmup Iteration   2: 5.824 ±(99.9%) 0.031 ms/op
# Warmup Iteration   3: 4.880 ±(99.9%) 0.018 ms/op
Iteration   1: 4.786 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.523 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.235 ms/op
                 listUser·p0.95:   6.128 ms/op
                 listUser·p0.99:   9.060 ms/op
                 listUser·p0.999:  24.515 ms/op
                 listUser·p0.9999: 27.230 ms/op
                 listUser·p1.00:   27.787 ms/op

Iteration   2: 5.104 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   2.060 ms/op
                 listUser·p0.50:   4.809 ms/op
                 listUser·p0.90:   6.210 ms/op
                 listUser·p0.95:   7.496 ms/op
                 listUser·p0.99:   9.373 ms/op
                 listUser·p0.999:  17.997 ms/op
                 listUser·p0.9999: 23.854 ms/op
                 listUser·p1.00:   25.035 ms/op

Iteration   3: 5.074 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.753 ms/op
                 listUser·p0.50:   4.850 ms/op
                 listUser·p0.90:   5.849 ms/op
                 listUser·p0.95:   6.849 ms/op
                 listUser·p0.99:   9.150 ms/op
                 listUser·p0.999:  17.957 ms/op
                 listUser·p0.9999: 19.794 ms/op
                 listUser·p1.00:   21.299 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 192661
  mean =      4.984 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 1 
    [ 2.500,  5.000) = 132052 
    [ 5.000,  7.500) = 53246 
    [ 7.500, 10.000) = 6286 
    [10.000, 12.500) = 641 
    [12.500, 15.000) = 51 
    [15.000, 17.500) = 85 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 109 
    [25.000, 27.500) = 43 

  Percentiles, ms/op:
      p(0.0000) =      2.060 ms/op
     p(50.0000) =      4.735 ms/op
     p(90.0000) =      5.784 ms/op
     p(95.0000) =      6.963 ms/op
     p(99.0000) =      9.241 ms/op
     p(99.9000) =     21.092 ms/op
     p(99.9900) =     26.287 ms/op
     p(99.9990) =     27.727 ms/op
     p(99.9999) =     27.787 ms/op
    p(100.0000) =     27.787 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.852 ± 9.260  ops/ms
ClientPb.existUser                       thrpt       3   7.975 ± 5.458  ops/ms
ClientPb.getUser                         thrpt       3   7.771 ± 4.775  ops/ms
ClientPb.listUser                        thrpt       3   6.832 ± 3.355  ops/ms
ClientPb.createUser                       avgt       3   4.014 ± 1.690   ms/op
ClientPb.existUser                        avgt       3   4.131 ± 0.590   ms/op
ClientPb.getUser                          avgt       3   3.936 ± 2.785   ms/op
ClientPb.listUser                         avgt       3   4.754 ± 3.344   ms/op
ClientPb.createUser                     sample  225645   4.252 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.421           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.043           ms/op
ClientPb.createUser:createUser·p0.90    sample           5.014           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.830           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.086           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.784           ms/op
ClientPb.createUser:createUser·p0.9999  sample          33.391           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.914           ms/op
ClientPb.existUser                      sample  238587   4.017 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.638           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.760           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.784           ms/op
ClientPb.existUser:existUser·p0.95      sample           5.456           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.750           ms/op
ClientPb.existUser:existUser·p0.999     sample          14.598           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.457           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.081           ms/op
ClientPb.getUser                        sample  229173   4.188 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.419           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.957           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.874           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.997           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.258           ms/op
ClientPb.getUser:getUser·p0.999         sample          17.787           ms/op
ClientPb.getUser:getUser·p0.9999        sample          30.411           ms/op
ClientPb.getUser:getUser·p1.00          sample          32.014           ms/op
ClientPb.listUser                       sample  192661   4.984 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.060           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.735           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.784           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.963           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.241           ms/op
ClientPb.listUser:listUser·p0.999       sample          21.092           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.287           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.787           ms/op
