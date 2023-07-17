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
# Warmup Iteration   1: 1.601 ops/ms
# Warmup Iteration   2: 3.681 ops/ms
# Warmup Iteration   3: 7.039 ops/ms
Iteration   1: 7.510 ops/ms
Iteration   2: 7.986 ops/ms
Iteration   3: 7.816 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.771 ±(99.9%) 4.404 ops/ms [Average]
  (min, avg, max) = (7.510, 7.771, 7.986), stdev = 0.241
  CI (99.9%): [3.367, 12.174] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:11
# Fork: 1 of 1
# Warmup Iteration   1: 2.608 ops/ms
# Warmup Iteration   2: 6.770 ops/ms
# Warmup Iteration   3: 8.061 ops/ms
Iteration   1: 8.424 ops/ms
Iteration   2: 8.422 ops/ms
Iteration   3: 8.498 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.448 ±(99.9%) 0.789 ops/ms [Average]
  (min, avg, max) = (8.422, 8.448, 8.498), stdev = 0.043
  CI (99.9%): [7.659, 9.237] (assumes normal distribution)


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
# Warmup Iteration   1: 2.434 ops/ms
# Warmup Iteration   2: 6.872 ops/ms
# Warmup Iteration   3: 7.892 ops/ms
Iteration   1: 8.071 ops/ms
Iteration   2: 8.178 ops/ms
Iteration   3: 8.216 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  8.155 ±(99.9%) 1.369 ops/ms [Average]
  (min, avg, max) = (8.071, 8.155, 8.216), stdev = 0.075
  CI (99.9%): [6.786, 9.524] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.926 ops/ms
# Warmup Iteration   2: 4.929 ops/ms
# Warmup Iteration   3: 6.581 ops/ms
Iteration   1: 6.692 ops/ms
Iteration   2: 6.936 ops/ms
Iteration   3: 6.838 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.822 ±(99.9%) 2.236 ops/ms [Average]
  (min, avg, max) = (6.692, 6.822, 6.936), stdev = 0.123
  CI (99.9%): [4.585, 9.058] (assumes normal distribution)


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
# Warmup Iteration   1: 11.764 ±(99.9%) 0.066 ms/op
# Warmup Iteration   2: 5.119 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.345 ±(99.9%) 0.006 ms/op
Iteration   1: 4.080 ±(99.9%) 0.012 ms/op
Iteration   2: 4.104 ±(99.9%) 0.008 ms/op
Iteration   3: 3.931 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.038 ±(99.9%) 1.710 ms/op [Average]
  (min, avg, max) = (3.931, 4.038, 4.104), stdev = 0.094
  CI (99.9%): [2.328, 5.748] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:43
# Fork: 1 of 1
# Warmup Iteration   1: 12.064 ±(99.9%) 0.043 ms/op
# Warmup Iteration   2: 4.293 ±(99.9%) 0.006 ms/op
# Warmup Iteration   3: 3.899 ±(99.9%) 0.006 ms/op
Iteration   1: 3.670 ±(99.9%) 0.009 ms/op
Iteration   2: 3.702 ±(99.9%) 0.010 ms/op
Iteration   3: 3.778 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.717 ±(99.9%) 1.011 ms/op [Average]
  (min, avg, max) = (3.670, 3.717, 3.778), stdev = 0.055
  CI (99.9%): [2.705, 4.728] (assumes normal distribution)


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
# Warmup Iteration   1: 13.319 ±(99.9%) 0.036 ms/op
# Warmup Iteration   2: 4.620 ±(99.9%) 0.005 ms/op
# Warmup Iteration   3: 4.113 ±(99.9%) 0.009 ms/op
Iteration   1: 4.005 ±(99.9%) 0.006 ms/op
Iteration   2: 3.912 ±(99.9%) 0.007 ms/op
Iteration   3: 3.957 ±(99.9%) 0.008 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.958 ±(99.9%) 0.848 ms/op [Average]
  (min, avg, max) = (3.912, 3.958, 4.005), stdev = 0.046
  CI (99.9%): [3.110, 4.806] (assumes normal distribution)


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
# Warmup Iteration   1: 14.170 ±(99.9%) 0.058 ms/op
# Warmup Iteration   2: 5.278 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 4.749 ±(99.9%) 0.009 ms/op
Iteration   1: 4.710 ±(99.9%) 0.011 ms/op
Iteration   2: 4.599 ±(99.9%) 0.010 ms/op
Iteration   3: 4.740 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.683 ±(99.9%) 1.356 ms/op [Average]
  (min, avg, max) = (4.599, 4.683, 4.740), stdev = 0.074
  CI (99.9%): [3.327, 6.039] (assumes normal distribution)


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
# Warmup Iteration   1: 13.140 ±(99.9%) 0.206 ms/op
# Warmup Iteration   2: 6.972 ±(99.9%) 0.055 ms/op
# Warmup Iteration   3: 4.341 ±(99.9%) 0.019 ms/op
Iteration   1: 4.063 ±(99.9%) 0.012 ms/op
                 createUser·p0.00:   1.976 ms/op
                 createUser·p0.50:   3.944 ms/op
                 createUser·p0.90:   4.588 ms/op
                 createUser·p0.95:   5.284 ms/op
                 createUser·p0.99:   7.897 ms/op
                 createUser·p0.999:  12.091 ms/op
                 createUser·p0.9999: 26.485 ms/op
                 createUser·p1.00:   27.263 ms/op

Iteration   2: 4.056 ±(99.9%) 0.013 ms/op
                 createUser·p0.00:   1.882 ms/op
                 createUser·p0.50:   3.863 ms/op
                 createUser·p0.90:   4.604 ms/op
                 createUser·p0.95:   5.071 ms/op
                 createUser·p0.99:   7.946 ms/op
                 createUser·p0.999:  24.675 ms/op
                 createUser·p0.9999: 27.594 ms/op
                 createUser·p1.00:   28.213 ms/op

Iteration   3: 4.061 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.100 ms/op
                 createUser·p0.50:   3.813 ms/op
                 createUser·p0.90:   4.628 ms/op
                 createUser·p0.95:   5.677 ms/op
                 createUser·p0.99:   8.159 ms/op
                 createUser·p0.999:  18.761 ms/op
                 createUser·p0.9999: 32.769 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 236490
  mean =      4.060 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 229 
    [ 2.500,  5.000) = 221274 
    [ 5.000,  7.500) = 11856 
    [ 7.500, 10.000) = 2199 
    [10.000, 12.500) = 569 
    [12.500, 15.000) = 84 
    [15.000, 17.500) = 31 
    [17.500, 20.000) = 14 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 49 
    [25.000, 27.500) = 103 
    [27.500, 30.000) = 33 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 9 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.100 ms/op
     p(50.0000) =      3.891 ms/op
     p(90.0000) =      4.612 ms/op
     p(95.0000) =      5.292 ms/op
     p(99.0000) =      8.036 ms/op
     p(99.9000) =     18.958 ms/op
     p(99.9900) =     31.710 ms/op
     p(99.9990) =     33.751 ms/op
     p(99.9999) =     33.882 ms/op
    p(100.0000) =     33.882 ms/op


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
# Warmup Iteration   1: 13.350 ±(99.9%) 0.191 ms/op
# Warmup Iteration   2: 4.662 ±(99.9%) 0.021 ms/op
# Warmup Iteration   3: 3.983 ±(99.9%) 0.013 ms/op
Iteration   1: 3.968 ±(99.9%) 0.013 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.772 ms/op
                 existUser·p0.90:   4.415 ms/op
                 existUser·p0.95:   5.071 ms/op
                 existUser·p0.99:   8.258 ms/op
                 existUser·p0.999:  23.285 ms/op
                 existUser·p0.9999: 26.016 ms/op
                 existUser·p1.00:   27.886 ms/op

Iteration   2: 3.764 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.056 ms/op
                 existUser·p0.50:   3.654 ms/op
                 existUser·p0.90:   3.973 ms/op
                 existUser·p0.95:   4.383 ms/op
                 existUser·p0.99:   6.830 ms/op
                 existUser·p0.999:  12.626 ms/op
                 existUser·p0.9999: 26.886 ms/op
                 existUser·p1.00:   28.475 ms/op

Iteration   3: 3.941 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   0.675 ms/op
                 existUser·p0.50:   3.789 ms/op
                 existUser·p0.90:   4.334 ms/op
                 existUser·p0.95:   5.063 ms/op
                 existUser·p0.99:   8.389 ms/op
                 existUser·p0.999:  24.740 ms/op
                 existUser·p0.9999: 29.098 ms/op
                 existUser·p1.00:   30.015 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 246925
  mean =      3.889 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 223 
    [ 2.500,  5.000) = 236126 
    [ 5.000,  7.500) = 7178 
    [ 7.500, 10.000) = 2584 
    [10.000, 12.500) = 413 
    [12.500, 15.000) = 124 
    [15.000, 17.500) = 21 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 85 
    [25.000, 27.500) = 127 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 1 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.675 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.276 ms/op
     p(95.0000) =      4.809 ms/op
     p(99.0000) =      8.020 ms/op
     p(99.9000) =     22.874 ms/op
     p(99.9900) =     28.067 ms/op
     p(99.9990) =     29.557 ms/op
     p(99.9999) =     30.015 ms/op
    p(100.0000) =     30.015 ms/op


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
# Warmup Iteration   1: 13.601 ±(99.9%) 0.192 ms/op
# Warmup Iteration   2: 5.171 ±(99.9%) 0.030 ms/op
# Warmup Iteration   3: 4.243 ±(99.9%) 0.014 ms/op
Iteration   1: 4.292 ±(99.9%) 0.015 ms/op
                 getUser·p0.00:   2.175 ms/op
                 getUser·p0.50:   4.026 ms/op
                 getUser·p0.90:   5.014 ms/op
                 getUser·p0.95:   5.751 ms/op
                 getUser·p0.99:   9.552 ms/op
                 getUser·p0.999:  20.395 ms/op
                 getUser·p0.9999: 25.282 ms/op
                 getUser·p1.00:   25.657 ms/op

Iteration   2: 3.918 ±(99.9%) 0.012 ms/op
                 getUser·p0.00:   1.446 ms/op
                 getUser·p0.50:   3.797 ms/op
                 getUser·p0.90:   4.235 ms/op
                 getUser·p0.95:   4.448 ms/op
                 getUser·p0.99:   6.685 ms/op
                 getUser·p0.999:  25.026 ms/op
                 getUser·p0.9999: 33.484 ms/op
                 getUser·p1.00:   34.275 ms/op

Iteration   3: 4.053 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.722 ms/op
                 getUser·p0.50:   3.879 ms/op
                 getUser·p0.90:   4.514 ms/op
                 getUser·p0.95:   4.923 ms/op
                 getUser·p0.99:   8.159 ms/op
                 getUser·p0.999:  26.363 ms/op
                 getUser·p0.9999: 32.550 ms/op
                 getUser·p1.00:   33.751 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 234975
  mean =      4.082 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 51 
    [ 2.500,  5.000) = 221810 
    [ 5.000,  7.500) = 9953 
    [ 7.500, 10.000) = 2085 
    [10.000, 12.500) = 600 
    [12.500, 15.000) = 90 
    [15.000, 17.500) = 90 
    [17.500, 20.000) = 30 
    [20.000, 22.500) = 10 
    [22.500, 25.000) = 62 
    [25.000, 27.500) = 87 
    [27.500, 30.000) = 50 
    [30.000, 32.500) = 37 
    [32.500, 35.000) = 20 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.446 ms/op
     p(50.0000) =      3.875 ms/op
     p(90.0000) =      4.645 ms/op
     p(95.0000) =      5.087 ms/op
     p(99.0000) =      8.348 ms/op
     p(99.9000) =     24.184 ms/op
     p(99.9900) =     32.326 ms/op
     p(99.9990) =     34.161 ms/op
     p(99.9999) =     34.275 ms/op
    p(100.0000) =     34.275 ms/op


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
# Warmup Iteration   1: 14.269 ±(99.9%) 0.215 ms/op
# Warmup Iteration   2: 5.470 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.812 ±(99.9%) 0.016 ms/op
Iteration   1: 4.853 ±(99.9%) 0.018 ms/op
                 listUser·p0.00:   1.686 ms/op
                 listUser·p0.50:   4.563 ms/op
                 listUser·p0.90:   5.620 ms/op
                 listUser·p0.95:   6.603 ms/op
                 listUser·p0.99:   8.978 ms/op
                 listUser·p0.999:  25.854 ms/op
                 listUser·p0.9999: 27.768 ms/op
                 listUser·p1.00:   28.213 ms/op

Iteration   2: 4.843 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.114 ms/op
                 listUser·p0.50:   4.620 ms/op
                 listUser·p0.90:   5.546 ms/op
                 listUser·p0.95:   6.341 ms/op
                 listUser·p0.99:   9.142 ms/op
                 listUser·p0.999:  16.384 ms/op
                 listUser·p0.9999: 21.842 ms/op
                 listUser·p1.00:   22.675 ms/op

Iteration   3: 4.783 ±(99.9%) 0.013 ms/op
                 listUser·p0.00:   1.720 ms/op
                 listUser·p0.50:   4.628 ms/op
                 listUser·p0.90:   5.177 ms/op
                 listUser·p0.95:   5.718 ms/op
                 listUser·p0.99:   8.899 ms/op
                 listUser·p0.999:  17.990 ms/op
                 listUser·p0.9999: 20.738 ms/op
                 listUser·p1.00:   21.561 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 198912
  mean =      4.826 ±(99.9%) 0.009 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16 
    [ 2.500,  5.000) = 158760 
    [ 5.000,  7.500) = 34226 
    [ 7.500, 10.000) = 4662 
    [10.000, 12.500) = 683 
    [12.500, 15.000) = 135 
    [15.000, 17.500) = 135 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 36 
    [22.500, 25.000) = 50 
    [25.000, 27.500) = 98 

  Percentiles, ms/op:
      p(0.0000) =      1.686 ms/op
     p(50.0000) =      4.604 ms/op
     p(90.0000) =      5.453 ms/op
     p(95.0000) =      6.291 ms/op
     p(99.0000) =      9.011 ms/op
     p(99.9000) =     19.270 ms/op
     p(99.9900) =     27.201 ms/op
     p(99.9990) =     28.181 ms/op
     p(99.9999) =     28.213 ms/op
    p(100.0000) =     28.213 ms/op


# Run complete. Total time: 00:13:17

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.771 ± 4.404  ops/ms
ClientPb.existUser                       thrpt       3   8.448 ± 0.789  ops/ms
ClientPb.getUser                         thrpt       3   8.155 ± 1.369  ops/ms
ClientPb.listUser                        thrpt       3   6.822 ± 2.236  ops/ms
ClientPb.createUser                       avgt       3   4.038 ± 1.710   ms/op
ClientPb.existUser                        avgt       3   3.717 ± 1.011   ms/op
ClientPb.getUser                          avgt       3   3.958 ± 0.848   ms/op
ClientPb.listUser                         avgt       3   4.683 ± 1.356   ms/op
ClientPb.createUser                     sample  236490   4.060 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.100           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.891           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.612           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.292           ms/op
ClientPb.createUser:createUser·p0.99    sample           8.036           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.958           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.710           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.882           ms/op
ClientPb.existUser                      sample  246925   3.889 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.675           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.276           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.809           ms/op
ClientPb.existUser:existUser·p0.99      sample           8.020           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.874           ms/op
ClientPb.existUser:existUser·p0.9999    sample          28.067           ms/op
ClientPb.existUser:existUser·p1.00      sample          30.015           ms/op
ClientPb.getUser                        sample  234975   4.082 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.446           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.875           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.645           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.087           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.348           ms/op
ClientPb.getUser:getUser·p0.999         sample          24.184           ms/op
ClientPb.getUser:getUser·p0.9999        sample          32.326           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.275           ms/op
ClientPb.listUser                       sample  198912   4.826 ± 0.009   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.686           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.604           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.453           ms/op
ClientPb.listUser:listUser·p0.95        sample           6.291           ms/op
ClientPb.listUser:listUser·p0.99        sample           9.011           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.270           ms/op
ClientPb.listUser:listUser·p0.9999      sample          27.201           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.213           ms/op
