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
# Warmup Iteration   1: 1.088 ops/ms
# Warmup Iteration   2: 2.196 ops/ms
# Warmup Iteration   3: 4.761 ops/ms
Iteration   1: 5.053 ops/ms
Iteration   2: 5.586 ops/ms
Iteration   3: 5.606 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.415 ±(99.9%) 5.729 ops/ms [Average]
  (min, avg, max) = (5.053, 5.415, 5.606), stdev = 0.314
  CI (99.9%): [≈ 0, 11.144] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:07
# Fork: 1 of 1
# Warmup Iteration   1: 1.467 ops/ms
# Warmup Iteration   2: 4.550 ops/ms
# Warmup Iteration   3: 5.795 ops/ms
Iteration   1: 5.754 ops/ms
Iteration   2: 6.140 ops/ms
Iteration   3: 5.862 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.918 ±(99.9%) 3.631 ops/ms [Average]
  (min, avg, max) = (5.754, 5.918, 6.140), stdev = 0.199
  CI (99.9%): [2.288, 9.549] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.348 ops/ms
# Warmup Iteration   2: 4.141 ops/ms
# Warmup Iteration   3: 5.379 ops/ms
Iteration   1: 5.331 ops/ms
Iteration   2: 5.635 ops/ms
Iteration   3: 5.481 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.483 ±(99.9%) 2.777 ops/ms [Average]
  (min, avg, max) = (5.331, 5.483, 5.635), stdev = 0.152
  CI (99.9%): [2.705, 8.260] (assumes normal distribution)


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
# Warmup Iteration   1: 1.530 ops/ms
# Warmup Iteration   2: 3.797 ops/ms
# Warmup Iteration   3: 4.741 ops/ms
Iteration   1: 4.431 ops/ms
Iteration   2: 4.735 ops/ms
Iteration   3: 4.780 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.649 ±(99.9%) 3.471 ops/ms [Average]
  (min, avg, max) = (4.431, 4.649, 4.780), stdev = 0.190
  CI (99.9%): [1.178, 8.119] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 18.362 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 7.001 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 5.968 ±(99.9%) 0.016 ms/op
Iteration   1: 5.886 ±(99.9%) 0.011 ms/op
Iteration   2: 5.640 ±(99.9%) 0.011 ms/op
Iteration   3: 5.793 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.773 ±(99.9%) 2.260 ms/op [Average]
  (min, avg, max) = (5.640, 5.773, 5.886), stdev = 0.124
  CI (99.9%): [3.512, 8.033] (assumes normal distribution)


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
# Warmup Iteration   1: 17.501 ±(99.9%) 0.082 ms/op
# Warmup Iteration   2: 6.600 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.797 ±(99.9%) 0.013 ms/op
Iteration   1: 5.403 ±(99.9%) 0.014 ms/op
Iteration   2: 5.276 ±(99.9%) 0.013 ms/op
Iteration   3: 5.335 ±(99.9%) 0.016 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.338 ±(99.9%) 1.158 ms/op [Average]
  (min, avg, max) = (5.276, 5.338, 5.403), stdev = 0.063
  CI (99.9%): [4.180, 6.496] (assumes normal distribution)


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
# Warmup Iteration   1: 18.390 ±(99.9%) 0.081 ms/op
# Warmup Iteration   2: 6.634 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.722 ±(99.9%) 0.011 ms/op
Iteration   1: 5.792 ±(99.9%) 0.016 ms/op
Iteration   2: 5.761 ±(99.9%) 0.013 ms/op
Iteration   3: 5.608 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.721 ±(99.9%) 1.798 ms/op [Average]
  (min, avg, max) = (5.608, 5.721, 5.792), stdev = 0.099
  CI (99.9%): [3.922, 7.519] (assumes normal distribution)


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
# Warmup Iteration   1: 22.943 ±(99.9%) 0.137 ms/op
# Warmup Iteration   2: 9.639 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.890 ±(99.9%) 0.015 ms/op
Iteration   1: 6.713 ±(99.9%) 0.013 ms/op
Iteration   2: 6.540 ±(99.9%) 0.019 ms/op
Iteration   3: 6.212 ±(99.9%) 0.021 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.488 ±(99.9%) 4.638 ms/op [Average]
  (min, avg, max) = (6.212, 6.488, 6.713), stdev = 0.254
  CI (99.9%): [1.850, 11.126] (assumes normal distribution)


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
# Warmup Iteration   1: 20.555 ±(99.9%) 0.335 ms/op
# Warmup Iteration   2: 7.835 ±(99.9%) 0.054 ms/op
# Warmup Iteration   3: 6.655 ±(99.9%) 0.036 ms/op
Iteration   1: 6.064 ±(99.9%) 0.026 ms/op
                 createUser·p0.00:   2.503 ms/op
                 createUser·p0.50:   5.612 ms/op
                 createUser·p0.90:   7.954 ms/op
                 createUser·p0.95:   9.093 ms/op
                 createUser·p0.99:   12.193 ms/op
                 createUser·p0.999:  27.853 ms/op
                 createUser·p0.9999: 31.238 ms/op
                 createUser·p1.00:   32.670 ms/op

Iteration   2: 5.711 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   1.835 ms/op
                 createUser·p0.50:   5.399 ms/op
                 createUser·p0.90:   7.168 ms/op
                 createUser·p0.95:   8.241 ms/op
                 createUser·p0.99:   10.994 ms/op
                 createUser·p0.999:  28.344 ms/op
                 createUser·p0.9999: 31.234 ms/op
                 createUser·p1.00:   31.719 ms/op

Iteration   3: 5.692 ±(99.9%) 0.025 ms/op
                 createUser·p0.00:   2.056 ms/op
                 createUser·p0.50:   5.308 ms/op
                 createUser·p0.90:   7.201 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   10.977 ms/op
                 createUser·p0.999:  32.664 ms/op
                 createUser·p0.9999: 35.615 ms/op
                 createUser·p1.00:   39.911 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 164936
  mean =      5.817 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 47817 
    [ 5.000,  7.500) = 101358 
    [ 7.500, 10.000) = 12442 
    [10.000, 12.500) = 2181 
    [12.500, 15.000) = 508 
    [15.000, 17.500) = 247 
    [17.500, 20.000) = 100 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 28 
    [25.000, 27.500) = 8 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 57 
    [32.500, 35.000) = 54 
    [35.000, 37.500) = 5 

  Percentiles, ms/op:
      p(0.0000) =      1.835 ms/op
     p(50.0000) =      5.439 ms/op
     p(90.0000) =      7.430 ms/op
     p(95.0000) =      8.520 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     28.641 ms/op
     p(99.9900) =     34.767 ms/op
     p(99.9990) =     39.826 ms/op
     p(99.9999) =     39.911 ms/op
    p(100.0000) =     39.911 ms/op


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
# Warmup Iteration   1: 16.124 ±(99.9%) 0.262 ms/op
# Warmup Iteration   2: 6.799 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.822 ±(99.9%) 0.023 ms/op
Iteration   1: 5.587 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.175 ms/op
                 existUser·p0.50:   5.218 ms/op
                 existUser·p0.90:   7.283 ms/op
                 existUser·p0.95:   8.274 ms/op
                 existUser·p0.99:   10.551 ms/op
                 existUser·p0.999:  15.852 ms/op
                 existUser·p0.9999: 31.410 ms/op
                 existUser·p1.00:   31.719 ms/op

Iteration   2: 5.534 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.142 ms/op
                 existUser·p0.50:   5.177 ms/op
                 existUser·p0.90:   7.021 ms/op
                 existUser·p0.95:   8.192 ms/op
                 existUser·p0.99:   11.108 ms/op
                 existUser·p0.999:  27.068 ms/op
                 existUser·p0.9999: 39.467 ms/op
                 existUser·p1.00:   39.715 ms/op

Iteration   3: 5.789 ±(99.9%) 0.027 ms/op
                 existUser·p0.00:   1.968 ms/op
                 existUser·p0.50:   5.325 ms/op
                 existUser·p0.90:   7.586 ms/op
                 existUser·p0.95:   8.897 ms/op
                 existUser·p0.99:   12.845 ms/op
                 existUser·p0.999:  30.813 ms/op
                 existUser·p0.9999: 40.370 ms/op
                 existUser·p1.00:   40.698 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170379
  mean =      5.635 ±(99.9%) 0.014 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 64049 
    [ 5.000, 10.000) = 102912 
    [10.000, 15.000) = 3005 
    [15.000, 20.000) = 243 
    [20.000, 25.000) = 8 
    [25.000, 30.000) = 58 
    [30.000, 35.000) = 40 
    [35.000, 40.000) = 53 
    [40.000, 45.000) = 11 

  Percentiles, ms/op:
      p(0.0000) =      1.968 ms/op
     p(50.0000) =      5.235 ms/op
     p(90.0000) =      7.324 ms/op
     p(95.0000) =      8.471 ms/op
     p(99.0000) =     11.370 ms/op
     p(99.9000) =     20.009 ms/op
     p(99.9900) =     39.453 ms/op
     p(99.9990) =     40.652 ms/op
     p(99.9999) =     40.698 ms/op
    p(100.0000) =     40.698 ms/op


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
# Warmup Iteration   1: 20.080 ±(99.9%) 0.380 ms/op
# Warmup Iteration   2: 6.983 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 5.711 ±(99.9%) 0.021 ms/op
Iteration   1: 5.690 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.216 ms/op
                 getUser·p0.50:   5.308 ms/op
                 getUser·p0.90:   7.291 ms/op
                 getUser·p0.95:   8.585 ms/op
                 getUser·p0.99:   11.239 ms/op
                 getUser·p0.999:  24.707 ms/op
                 getUser·p0.9999: 29.471 ms/op
                 getUser·p1.00:   29.852 ms/op

Iteration   2: 5.631 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.251 ms/op
                 getUser·p0.90:   7.152 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   11.996 ms/op
                 getUser·p0.999:  19.872 ms/op
                 getUser·p0.9999: 34.140 ms/op
                 getUser·p1.00:   35.586 ms/op

Iteration   3: 5.714 ±(99.9%) 0.023 ms/op
                 getUser·p0.00:   2.087 ms/op
                 getUser·p0.50:   5.341 ms/op
                 getUser·p0.90:   7.307 ms/op
                 getUser·p0.95:   8.315 ms/op
                 getUser·p0.99:   11.272 ms/op
                 getUser·p0.999:  31.982 ms/op
                 getUser·p0.9999: 36.700 ms/op
                 getUser·p1.00:   37.290 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 169116
  mean =      5.678 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 8 
    [ 2.500,  5.000) = 57790 
    [ 5.000,  7.500) = 96805 
    [ 7.500, 10.000) = 11064 
    [10.000, 12.500) = 2280 
    [12.500, 15.000) = 675 
    [15.000, 17.500) = 191 
    [17.500, 20.000) = 81 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 19 
    [25.000, 27.500) = 40 
    [27.500, 30.000) = 25 
    [30.000, 32.500) = 23 
    [32.500, 35.000) = 36 
    [35.000, 37.500) = 37 

  Percentiles, ms/op:
      p(0.0000) =      2.087 ms/op
     p(50.0000) =      5.300 ms/op
     p(90.0000) =      7.250 ms/op
     p(95.0000) =      8.405 ms/op
     p(99.0000) =     11.502 ms/op
     p(99.9000) =     24.634 ms/op
     p(99.9900) =     36.176 ms/op
     p(99.9990) =     37.018 ms/op
     p(99.9999) =     37.290 ms/op
    p(100.0000) =     37.290 ms/op


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
# Warmup Iteration   1: 21.294 ±(99.9%) 0.367 ms/op
# Warmup Iteration   2: 8.689 ±(99.9%) 0.064 ms/op
# Warmup Iteration   3: 6.856 ±(99.9%) 0.030 ms/op
Iteration   1: 6.877 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.933 ms/op
                 listUser·p0.50:   6.431 ms/op
                 listUser·p0.90:   8.716 ms/op
                 listUser·p0.95:   9.945 ms/op
                 listUser·p0.99:   13.217 ms/op
                 listUser·p0.999:  29.815 ms/op
                 listUser·p0.9999: 31.940 ms/op
                 listUser·p1.00:   35.127 ms/op

Iteration   2: 6.764 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   2.013 ms/op
                 listUser·p0.50:   6.382 ms/op
                 listUser·p0.90:   8.339 ms/op
                 listUser·p0.95:   9.503 ms/op
                 listUser·p0.99:   13.206 ms/op
                 listUser·p0.999:  33.414 ms/op
                 listUser·p0.9999: 35.866 ms/op
                 listUser·p1.00:   36.831 ms/op

Iteration   3: 7.126 ±(99.9%) 0.029 ms/op
                 listUser·p0.00:   2.593 ms/op
                 listUser·p0.50:   6.701 ms/op
                 listUser·p0.90:   9.126 ms/op
                 listUser·p0.95:   10.306 ms/op
                 listUser·p0.99:   13.582 ms/op
                 listUser·p0.999:  27.363 ms/op
                 listUser·p0.9999: 32.442 ms/op
                 listUser·p1.00:   34.079 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 138734
  mean =      6.919 ±(99.9%) 0.017 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 2975 
    [ 5.000,  7.500) = 105387 
    [ 7.500, 10.000) = 23716 
    [10.000, 12.500) = 4743 
    [12.500, 15.000) = 1234 
    [15.000, 17.500) = 328 
    [17.500, 20.000) = 48 
    [20.000, 22.500) = 18 
    [22.500, 25.000) = 20 
    [25.000, 27.500) = 53 
    [27.500, 30.000) = 46 
    [30.000, 32.500) = 91 
    [32.500, 35.000) = 59 
    [35.000, 37.500) = 12 

  Percentiles, ms/op:
      p(0.0000) =      2.013 ms/op
     p(50.0000) =      6.504 ms/op
     p(90.0000) =      8.733 ms/op
     p(95.0000) =      9.933 ms/op
     p(99.0000) =     13.347 ms/op
     p(99.9000) =     30.835 ms/op
     p(99.9900) =     34.882 ms/op
     p(99.9990) =     36.628 ms/op
     p(99.9999) =     36.831 ms/op
    p(100.0000) =     36.831 ms/op


# Run complete. Total time: 00:13:22

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.415 ± 5.729  ops/ms
ClientPb.existUser                       thrpt       3   5.918 ± 3.631  ops/ms
ClientPb.getUser                         thrpt       3   5.483 ± 2.777  ops/ms
ClientPb.listUser                        thrpt       3   4.649 ± 3.471  ops/ms
ClientPb.createUser                       avgt       3   5.773 ± 2.260   ms/op
ClientPb.existUser                        avgt       3   5.338 ± 1.158   ms/op
ClientPb.getUser                          avgt       3   5.721 ± 1.798   ms/op
ClientPb.listUser                         avgt       3   6.488 ± 4.638   ms/op
ClientPb.createUser                     sample  164936   5.817 ± 0.014   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.835           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.439           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.430           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.520           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.354           ms/op
ClientPb.createUser:createUser·p0.999   sample          28.641           ms/op
ClientPb.createUser:createUser·p0.9999  sample          34.767           ms/op
ClientPb.createUser:createUser·p1.00    sample          39.911           ms/op
ClientPb.existUser                      sample  170379   5.635 ± 0.014   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.968           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.235           ms/op
ClientPb.existUser:existUser·p0.90      sample           7.324           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.471           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.370           ms/op
ClientPb.existUser:existUser·p0.999     sample          20.009           ms/op
ClientPb.existUser:existUser·p0.9999    sample          39.453           ms/op
ClientPb.existUser:existUser·p1.00      sample          40.698           ms/op
ClientPb.getUser                        sample  169116   5.678 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.087           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.300           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.250           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.405           ms/op
ClientPb.getUser:getUser·p0.99          sample          11.502           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.634           ms/op
ClientPb.getUser:getUser·p0.9999        sample          36.176           ms/op
ClientPb.getUser:getUser·p1.00          sample          37.290           ms/op
ClientPb.listUser                       sample  138734   6.919 ± 0.017   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.013           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.504           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.733           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.933           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.347           ms/op
ClientPb.listUser:listUser·p0.999       sample          30.835           ms/op
ClientPb.listUser:listUser·p0.9999      sample          34.882           ms/op
ClientPb.listUser:listUser·p1.00        sample          36.831           ms/op
