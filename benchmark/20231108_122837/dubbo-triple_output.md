# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 0.00% complete, ETA 00:12:00
# Fork: 1 of 1
# Warmup Iteration   1: 1.068 ops/ms
# Warmup Iteration   2: 2.358 ops/ms
# Warmup Iteration   3: 4.996 ops/ms
Iteration   1: 5.558 ops/ms
Iteration   2: 5.748 ops/ms
Iteration   3: 5.844 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.717 ±(99.9%) 2.660 ops/ms [Average]
  (min, avg, max) = (5.558, 5.717, 5.844), stdev = 0.146
  CI (99.9%): [3.057, 8.377] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 8.33% complete, ETA 00:12:06
# Fork: 1 of 1
# Warmup Iteration   1: 1.532 ops/ms
# Warmup Iteration   2: 5.074 ops/ms
# Warmup Iteration   3: 6.246 ops/ms
Iteration   1: 6.195 ops/ms
Iteration   2: 6.356 ops/ms
Iteration   3: 6.645 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.399 ±(99.9%) 4.159 ops/ms [Average]
  (min, avg, max) = (6.195, 6.399, 6.645), stdev = 0.228
  CI (99.9%): [2.240, 10.558] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 16.67% complete, ETA 00:11:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.822 ops/ms
# Warmup Iteration   2: 5.166 ops/ms
# Warmup Iteration   3: 6.238 ops/ms
Iteration   1: 6.317 ops/ms
Iteration   2: 6.353 ops/ms
Iteration   3: 6.451 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  6.373 ±(99.9%) 1.263 ops/ms [Average]
  (min, avg, max) = (6.317, 6.373, 6.451), stdev = 0.069
  CI (99.9%): [5.110, 7.637] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Throughput, ops/time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 25.00% complete, ETA 00:09:55
# Fork: 1 of 1
# Warmup Iteration   1: 1.878 ops/ms
# Warmup Iteration   2: 4.523 ops/ms
# Warmup Iteration   3: 5.327 ops/ms
Iteration   1: 5.677 ops/ms
Iteration   2: 5.376 ops/ms
Iteration   3: 5.396 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.483 ±(99.9%) 3.071 ops/ms [Average]
  (min, avg, max) = (5.376, 5.483, 5.677), stdev = 0.168
  CI (99.9%): [2.412, 8.555] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 33.33% complete, ETA 00:08:50
# Fork: 1 of 1
# Warmup Iteration   1: 17.038 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 6.380 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.571 ±(99.9%) 0.007 ms/op
Iteration   1: 5.098 ±(99.9%) 0.014 ms/op
Iteration   2: 5.202 ±(99.9%) 0.009 ms/op
Iteration   3: 5.177 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.159 ±(99.9%) 0.990 ms/op [Average]
  (min, avg, max) = (5.098, 5.159, 5.202), stdev = 0.054
  CI (99.9%): [4.169, 6.149] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 41.67% complete, ETA 00:07:44
# Fork: 1 of 1
# Warmup Iteration   1: 14.781 ±(99.9%) 0.071 ms/op
# Warmup Iteration   2: 5.482 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 5.151 ±(99.9%) 0.007 ms/op
Iteration   1: 5.081 ±(99.9%) 0.006 ms/op
Iteration   2: 4.861 ±(99.9%) 0.012 ms/op
Iteration   3: 4.924 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  4.955 ±(99.9%) 2.066 ms/op [Average]
  (min, avg, max) = (4.861, 4.955, 5.081), stdev = 0.113
  CI (99.9%): [2.890, 7.021] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 50.00% complete, ETA 00:06:38
# Fork: 1 of 1
# Warmup Iteration   1: 16.828 ±(99.9%) 0.094 ms/op
# Warmup Iteration   2: 6.438 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 5.160 ±(99.9%) 0.009 ms/op
Iteration   1: 5.109 ±(99.9%) 0.005 ms/op
Iteration   2: 5.198 ±(99.9%) 0.008 ms/op
Iteration   3: 5.382 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.230 ±(99.9%) 2.534 ms/op [Average]
  (min, avg, max) = (5.109, 5.230, 5.382), stdev = 0.139
  CI (99.9%): [2.696, 7.763] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Average time, time/op
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 58.33% complete, ETA 00:05:32
# Fork: 1 of 1
# Warmup Iteration   1: 17.923 ±(99.9%) 0.083 ms/op
# Warmup Iteration   2: 6.930 ±(99.9%) 0.020 ms/op
# Warmup Iteration   3: 6.228 ±(99.9%) 0.013 ms/op
Iteration   1: 5.896 ±(99.9%) 0.015 ms/op
Iteration   2: 6.277 ±(99.9%) 0.012 ms/op
Iteration   3: 5.897 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.023 ±(99.9%) 4.013 ms/op [Average]
  (min, avg, max) = (5.896, 6.023, 6.277), stdev = 0.220
  CI (99.9%): [2.011, 10.036] (assumes normal distribution)


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.createUser

# Run progress: 66.67% complete, ETA 00:04:25
# Fork: 1 of 1
# Warmup Iteration   1: 16.190 ±(99.9%) 0.235 ms/op
# Warmup Iteration   2: 5.905 ±(99.9%) 0.028 ms/op
# Warmup Iteration   3: 5.451 ±(99.9%) 0.022 ms/op
Iteration   1: 5.115 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.179 ms/op
                 createUser·p0.50:   4.907 ms/op
                 createUser·p0.90:   6.136 ms/op
                 createUser·p0.95:   6.693 ms/op
                 createUser·p0.99:   8.852 ms/op
                 createUser·p0.999:  23.449 ms/op
                 createUser·p0.9999: 27.623 ms/op
                 createUser·p1.00:   29.000 ms/op

Iteration   2: 5.091 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.212 ms/op
                 createUser·p0.50:   4.866 ms/op
                 createUser·p0.90:   6.193 ms/op
                 createUser·p0.95:   6.709 ms/op
                 createUser·p0.99:   8.552 ms/op
                 createUser·p0.999:  24.702 ms/op
                 createUser·p0.9999: 29.735 ms/op
                 createUser·p1.00:   31.261 ms/op

Iteration   3: 5.026 ±(99.9%) 0.016 ms/op
                 createUser·p0.00:   2.208 ms/op
                 createUser·p0.50:   4.768 ms/op
                 createUser·p0.90:   6.087 ms/op
                 createUser·p0.95:   6.865 ms/op
                 createUser·p0.99:   9.224 ms/op
                 createUser·p0.999:  24.058 ms/op
                 createUser·p0.9999: 30.935 ms/op
                 createUser·p1.00:   31.457 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 189058
  mean =      5.077 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 103 
    [ 2.500,  5.000) = 110551 
    [ 5.000,  7.500) = 73450 
    [ 7.500, 10.000) = 3803 
    [10.000, 12.500) = 631 
    [12.500, 15.000) = 283 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 8 
    [22.500, 25.000) = 44 
    [25.000, 27.500) = 90 
    [27.500, 30.000) = 49 
    [30.000, 32.500) = 10 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.179 ms/op
     p(50.0000) =      4.850 ms/op
     p(90.0000) =      6.144 ms/op
     p(95.0000) =      6.750 ms/op
     p(99.0000) =      8.929 ms/op
     p(99.9000) =     23.853 ms/op
     p(99.9900) =     29.429 ms/op
     p(99.9990) =     31.311 ms/op
     p(99.9999) =     31.457 ms/op
    p(100.0000) =     31.457 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.existUser

# Run progress: 75.00% complete, ETA 00:03:19
# Fork: 1 of 1
# Warmup Iteration   1: 14.080 ±(99.9%) 0.227 ms/op
# Warmup Iteration   2: 5.373 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 5.077 ±(99.9%) 0.017 ms/op
Iteration   1: 5.049 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.821 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.210 ms/op
                 existUser·p0.95:   7.070 ms/op
                 existUser·p0.99:   9.437 ms/op
                 existUser·p0.999:  24.937 ms/op
                 existUser·p0.9999: 28.016 ms/op
                 existUser·p1.00:   29.393 ms/op

Iteration   2: 5.027 ±(99.9%) 0.017 ms/op
                 existUser·p0.00:   1.870 ms/op
                 existUser·p0.50:   4.760 ms/op
                 existUser·p0.90:   6.103 ms/op
                 existUser·p0.95:   6.939 ms/op
                 existUser·p0.99:   9.044 ms/op
                 existUser·p0.999:  23.597 ms/op
                 existUser·p0.9999: 28.332 ms/op
                 existUser·p1.00:   29.360 ms/op

Iteration   3: 5.178 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   2.083 ms/op
                 existUser·p0.50:   4.899 ms/op
                 existUser·p0.90:   6.283 ms/op
                 existUser·p0.95:   7.029 ms/op
                 existUser·p0.99:   9.421 ms/op
                 existUser·p0.999:  28.572 ms/op
                 existUser·p0.9999: 36.623 ms/op
                 existUser·p1.00:   37.487 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 188754
  mean =      5.084 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 57 
    [ 2.500,  5.000) = 116907 
    [ 5.000,  7.500) = 65136 
    [ 7.500, 10.000) = 5227 
    [10.000, 12.500) = 600 
    [12.500, 15.000) = 445 
    [15.000, 17.500) = 123 
    [17.500, 20.000) = 50 
    [20.000, 22.500) = 12 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 86 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 11 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 29 

  Percentiles, ms/op:
      p(0.0000) =      1.821 ms/op
     p(50.0000) =      4.809 ms/op
     p(90.0000) =      6.210 ms/op
     p(95.0000) =      7.021 ms/op
     p(99.0000) =      9.372 ms/op
     p(99.9000) =     23.888 ms/op
     p(99.9900) =     35.848 ms/op
     p(99.9990) =     37.196 ms/op
     p(99.9999) =     37.487 ms/op
    p(100.0000) =     37.487 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 15.622 ±(99.9%) 0.290 ms/op
# Warmup Iteration   2: 6.376 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 5.453 ±(99.9%) 0.022 ms/op
Iteration   1: 5.141 ±(99.9%) 0.016 ms/op
                 getUser·p0.00:   1.542 ms/op
                 getUser·p0.50:   4.907 ms/op
                 getUser·p0.90:   6.062 ms/op
                 getUser·p0.95:   6.717 ms/op
                 getUser·p0.99:   9.355 ms/op
                 getUser·p0.999:  22.505 ms/op
                 getUser·p0.9999: 26.600 ms/op
                 getUser·p1.00:   28.017 ms/op

Iteration   2: 5.183 ±(99.9%) 0.020 ms/op
                 getUser·p0.00:   2.662 ms/op
                 getUser·p0.50:   4.874 ms/op
                 getUser·p0.90:   6.308 ms/op
                 getUser·p0.95:   7.258 ms/op
                 getUser·p0.99:   10.011 ms/op
                 getUser·p0.999:  26.868 ms/op
                 getUser·p0.9999: 31.818 ms/op
                 getUser·p1.00:   35.389 ms/op

Iteration   3: 5.045 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   0.999 ms/op
                 getUser·p0.50:   4.891 ms/op
                 getUser·p0.90:   5.931 ms/op
                 getUser·p0.95:   6.470 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  24.008 ms/op
                 getUser·p0.9999: 31.064 ms/op
                 getUser·p1.00:   32.440 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 187187
  mean =      5.122 ±(99.9%) 0.010 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 108051 
    [ 5.000,  7.500) = 73162 
    [ 7.500, 10.000) = 4579 
    [10.000, 12.500) = 685 
    [12.500, 15.000) = 309 
    [15.000, 17.500) = 78 
    [17.500, 20.000) = 51 
    [20.000, 22.500) = 48 
    [22.500, 25.000) = 66 
    [25.000, 27.500) = 58 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 40 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.999 ms/op
     p(50.0000) =      4.891 ms/op
     p(90.0000) =      6.078 ms/op
     p(95.0000) =      6.775 ms/op
     p(99.0000) =      9.355 ms/op
     p(99.9000) =     23.744 ms/op
     p(99.9900) =     31.466 ms/op
     p(99.9990) =     32.818 ms/op
     p(99.9999) =     35.389 ms/op
    p(100.0000) =     35.389 ms/op


# JMH version: 1.21
# VM version: JDK 1.8.0_392, OpenJDK 64-Bit Server VM, 25.392-b08
# VM invoker: /opt/hostedtoolcache/Java_Adopt_jdk/8.0.392-8/x64/jre/bin/java
# VM options: -Xmx1g -Xms1g -XX:MaxDirectMemorySize=1g -XX:+UseG1GC -Dserver.host=localhost -Dserver.port=8080 -Dbenchmark.output=dubbo-triple_output.md
# Warmup: 3 iterations, 10 s each
# Measurement: 3 iterations, 10 s each
# Timeout: 10 min per iteration
# Threads: 32 threads, will synchronize iterations
# Benchmark mode: Sampling time
# Benchmark: org.apache.dubbo.benchmark.ClientPb.listUser

# Run progress: 91.67% complete, ETA 00:01:06
# Fork: 1 of 1
# Warmup Iteration   1: 18.009 ±(99.9%) 0.276 ms/op
# Warmup Iteration   2: 6.653 ±(99.9%) 0.035 ms/op
# Warmup Iteration   3: 6.184 ±(99.9%) 0.024 ms/op
Iteration   1: 5.801 ±(99.9%) 0.020 ms/op
                 listUser·p0.00:   2.843 ms/op
                 listUser·p0.50:   5.546 ms/op
                 listUser·p0.90:   6.611 ms/op
                 listUser·p0.95:   7.422 ms/op
                 listUser·p0.99:   10.519 ms/op
                 listUser·p0.999:  26.536 ms/op
                 listUser·p0.9999: 30.309 ms/op
                 listUser·p1.00:   31.097 ms/op

Iteration   2: 5.899 ±(99.9%) 0.019 ms/op
                 listUser·p0.00:   2.331 ms/op
                 listUser·p0.50:   5.685 ms/op
                 listUser·p0.90:   6.701 ms/op
                 listUser·p0.95:   7.365 ms/op
                 listUser·p0.99:   10.420 ms/op
                 listUser·p0.999:  26.066 ms/op
                 listUser·p0.9999: 29.835 ms/op
                 listUser·p1.00:   30.573 ms/op

Iteration   3: 5.858 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   2.224 ms/op
                 listUser·p0.50:   5.562 ms/op
                 listUser·p0.90:   6.906 ms/op
                 listUser·p0.95:   7.766 ms/op
                 listUser·p0.99:   10.715 ms/op
                 listUser·p0.999:  19.169 ms/op
                 listUser·p0.9999: 23.331 ms/op
                 listUser·p1.00:   23.364 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 164002
  mean =      5.852 ±(99.9%) 0.011 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 3 
    [ 2.500,  5.000) = 15048 
    [ 5.000,  7.500) = 140576 
    [ 7.500, 10.000) = 6097 
    [10.000, 12.500) = 1456 
    [12.500, 15.000) = 308 
    [15.000, 17.500) = 159 
    [17.500, 20.000) = 94 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 73 
    [25.000, 27.500) = 81 
    [27.500, 30.000) = 54 
    [30.000, 32.500) = 14 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.224 ms/op
     p(50.0000) =      5.603 ms/op
     p(90.0000) =      6.726 ms/op
     p(95.0000) =      7.528 ms/op
     p(99.0000) =     10.519 ms/op
     p(99.9000) =     24.510 ms/op
     p(99.9900) =     29.937 ms/op
     p(99.9990) =     30.761 ms/op
     p(99.9999) =     31.097 ms/op
    p(100.0000) =     31.097 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.717 ± 2.660  ops/ms
ClientPb.existUser                       thrpt       3   6.399 ± 4.159  ops/ms
ClientPb.getUser                         thrpt       3   6.373 ± 1.263  ops/ms
ClientPb.listUser                        thrpt       3   5.483 ± 3.071  ops/ms
ClientPb.createUser                       avgt       3   5.159 ± 0.990   ms/op
ClientPb.existUser                        avgt       3   4.955 ± 2.066   ms/op
ClientPb.getUser                          avgt       3   5.230 ± 2.534   ms/op
ClientPb.listUser                         avgt       3   6.023 ± 4.013   ms/op
ClientPb.createUser                     sample  189058   5.077 ± 0.009   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.179           ms/op
ClientPb.createUser:createUser·p0.50    sample           4.850           ms/op
ClientPb.createUser:createUser·p0.90    sample           6.144           ms/op
ClientPb.createUser:createUser·p0.95    sample           6.750           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.929           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.853           ms/op
ClientPb.createUser:createUser·p0.9999  sample          29.429           ms/op
ClientPb.createUser:createUser·p1.00    sample          31.457           ms/op
ClientPb.existUser                      sample  188754   5.084 ± 0.010   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.821           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.210           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.021           ms/op
ClientPb.existUser:existUser·p0.99      sample           9.372           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.888           ms/op
ClientPb.existUser:existUser·p0.9999    sample          35.848           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.487           ms/op
ClientPb.getUser                        sample  187187   5.122 ± 0.010   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.999           ms/op
ClientPb.getUser:getUser·p0.50          sample           4.891           ms/op
ClientPb.getUser:getUser·p0.90          sample           6.078           ms/op
ClientPb.getUser:getUser·p0.95          sample           6.775           ms/op
ClientPb.getUser:getUser·p0.99          sample           9.355           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.744           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.466           ms/op
ClientPb.getUser:getUser·p1.00          sample          35.389           ms/op
ClientPb.listUser                       sample  164002   5.852 ± 0.011   ms/op
ClientPb.listUser:listUser·p0.00        sample           2.224           ms/op
ClientPb.listUser:listUser·p0.50        sample           5.603           ms/op
ClientPb.listUser:listUser·p0.90        sample           6.726           ms/op
ClientPb.listUser:listUser·p0.95        sample           7.528           ms/op
ClientPb.listUser:listUser·p0.99        sample          10.519           ms/op
ClientPb.listUser:listUser·p0.999       sample          24.510           ms/op
ClientPb.listUser:listUser·p0.9999      sample          29.937           ms/op
ClientPb.listUser:listUser·p1.00        sample          31.097           ms/op
