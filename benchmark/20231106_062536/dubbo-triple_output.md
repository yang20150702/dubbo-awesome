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
# Warmup Iteration   1: 1.064 ops/ms
# Warmup Iteration   2: 2.573 ops/ms
# Warmup Iteration   3: 5.246 ops/ms
Iteration   1: 5.484 ops/ms
Iteration   2: 5.688 ops/ms
Iteration   3: 5.951 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.708 ±(99.9%) 4.276 ops/ms [Average]
  (min, avg, max) = (5.484, 5.708, 5.951), stdev = 0.234
  CI (99.9%): [1.431, 9.984] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:04
# Fork: 1 of 1
# Warmup Iteration   1: 1.810 ops/ms
# Warmup Iteration   2: 5.184 ops/ms
# Warmup Iteration   3: 5.932 ops/ms
Iteration   1: 6.104 ops/ms
Iteration   2: 6.379 ops/ms
Iteration   3: 6.184 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  6.223 ±(99.9%) 2.582 ops/ms [Average]
  (min, avg, max) = (6.104, 6.223, 6.379), stdev = 0.142
  CI (99.9%): [3.641, 8.804] (assumes normal distribution)


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

# Run progress: 16.67% complete, ETA 00:11:03
# Fork: 1 of 1
# Warmup Iteration   1: 1.458 ops/ms
# Warmup Iteration   2: 4.263 ops/ms
# Warmup Iteration   3: 5.464 ops/ms
Iteration   1: 5.581 ops/ms
Iteration   2: 5.728 ops/ms
Iteration   3: 6.022 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.777 ±(99.9%) 4.101 ops/ms [Average]
  (min, avg, max) = (5.581, 5.777, 6.022), stdev = 0.225
  CI (99.9%): [1.676, 9.878] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:57
# Fork: 1 of 1
# Warmup Iteration   1: 1.594 ops/ms
# Warmup Iteration   2: 3.834 ops/ms
# Warmup Iteration   3: 4.986 ops/ms
Iteration   1: 5.009 ops/ms
Iteration   2: 5.322 ops/ms
Iteration   3: 5.102 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  5.144 ±(99.9%) 2.930 ops/ms [Average]
  (min, avg, max) = (5.009, 5.144, 5.322), stdev = 0.161
  CI (99.9%): [2.215, 8.074] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:51
# Fork: 1 of 1
# Warmup Iteration   1: 19.388 ±(99.9%) 0.124 ms/op
# Warmup Iteration   2: 7.390 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.831 ±(99.9%) 0.013 ms/op
Iteration   1: 5.680 ±(99.9%) 0.012 ms/op
Iteration   2: 5.533 ±(99.9%) 0.015 ms/op
Iteration   3: 5.448 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.554 ±(99.9%) 2.139 ms/op [Average]
  (min, avg, max) = (5.448, 5.554, 5.680), stdev = 0.117
  CI (99.9%): [3.415, 7.693] (assumes normal distribution)


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
# Warmup Iteration   1: 16.471 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 6.758 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.459 ±(99.9%) 0.009 ms/op
Iteration   1: 5.352 ±(99.9%) 0.013 ms/op
Iteration   2: 5.249 ±(99.9%) 0.009 ms/op
Iteration   3: 5.265 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.289 ±(99.9%) 1.012 ms/op [Average]
  (min, avg, max) = (5.249, 5.289, 5.352), stdev = 0.055
  CI (99.9%): [4.276, 6.301] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:37
# Fork: 1 of 1
# Warmup Iteration   1: 15.461 ±(99.9%) 0.062 ms/op
# Warmup Iteration   2: 6.421 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 5.655 ±(99.9%) 0.010 ms/op
Iteration   1: 5.682 ±(99.9%) 0.010 ms/op
Iteration   2: 5.486 ±(99.9%) 0.008 ms/op
Iteration   3: 5.435 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.534 ±(99.9%) 2.377 ms/op [Average]
  (min, avg, max) = (5.435, 5.534, 5.682), stdev = 0.130
  CI (99.9%): [3.157, 7.911] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:31
# Fork: 1 of 1
# Warmup Iteration   1: 18.481 ±(99.9%) 0.067 ms/op
# Warmup Iteration   2: 7.496 ±(99.9%) 0.009 ms/op
# Warmup Iteration   3: 6.388 ±(99.9%) 0.013 ms/op
Iteration   1: 6.280 ±(99.9%) 0.013 ms/op
Iteration   2: 6.178 ±(99.9%) 0.009 ms/op
Iteration   3: 6.440 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.299 ±(99.9%) 2.407 ms/op [Average]
  (min, avg, max) = (6.178, 6.299, 6.440), stdev = 0.132
  CI (99.9%): [3.893, 8.706] (assumes normal distribution)


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
# Warmup Iteration   1: 18.842 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 7.816 ±(99.9%) 0.061 ms/op
# Warmup Iteration   3: 5.762 ±(99.9%) 0.026 ms/op
Iteration   1: 5.585 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.122 ms/op
                 createUser·p0.50:   5.087 ms/op
                 createUser·p0.90:   7.250 ms/op
                 createUser·p0.95:   8.667 ms/op
                 createUser·p0.99:   12.370 ms/op
                 createUser·p0.999:  22.266 ms/op
                 createUser·p0.9999: 25.095 ms/op
                 createUser·p1.00:   26.280 ms/op

Iteration   2: 5.580 ±(99.9%) 0.023 ms/op
                 createUser·p0.00:   1.860 ms/op
                 createUser·p0.50:   5.145 ms/op
                 createUser·p0.90:   7.225 ms/op
                 createUser·p0.95:   8.315 ms/op
                 createUser·p0.99:   12.227 ms/op
                 createUser·p0.999:  23.387 ms/op
                 createUser·p0.9999: 31.016 ms/op
                 createUser·p1.00:   32.473 ms/op

Iteration   3: 5.554 ±(99.9%) 0.021 ms/op
                 createUser·p0.00:   2.359 ms/op
                 createUser·p0.50:   5.194 ms/op
                 createUser·p0.90:   7.012 ms/op
                 createUser·p0.95:   8.102 ms/op
                 createUser·p0.99:   11.387 ms/op
                 createUser·p0.999:  17.596 ms/op
                 createUser·p0.9999: 29.786 ms/op
                 createUser·p1.00:   30.507 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 172073
  mean =      5.573 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 31 
    [ 2.500,  5.000) = 74936 
    [ 5.000,  7.500) = 83156 
    [ 7.500, 10.000) = 10049 
    [10.000, 12.500) = 2530 
    [12.500, 15.000) = 758 
    [15.000, 17.500) = 295 
    [17.500, 20.000) = 120 
    [20.000, 22.500) = 49 
    [22.500, 25.000) = 64 
    [25.000, 27.500) = 23 
    [27.500, 30.000) = 37 
    [30.000, 32.500) = 25 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.860 ms/op
     p(50.0000) =      5.136 ms/op
     p(90.0000) =      7.152 ms/op
     p(95.0000) =      8.331 ms/op
     p(99.0000) =     11.911 ms/op
     p(99.9000) =     21.658 ms/op
     p(99.9900) =     30.402 ms/op
     p(99.9990) =     32.449 ms/op
     p(99.9999) =     32.473 ms/op
    p(100.0000) =     32.473 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:18
# Fork: 1 of 1
# Warmup Iteration   1: 16.049 ±(99.9%) 0.260 ms/op
# Warmup Iteration   2: 6.421 ±(99.9%) 0.037 ms/op
# Warmup Iteration   3: 5.462 ±(99.9%) 0.022 ms/op
Iteration   1: 5.443 ±(99.9%) 0.019 ms/op
                 existUser·p0.00:   1.821 ms/op
                 existUser·p0.50:   5.120 ms/op
                 existUser·p0.90:   6.930 ms/op
                 existUser·p0.95:   7.835 ms/op
                 existUser·p0.99:   10.846 ms/op
                 existUser·p0.999:  15.368 ms/op
                 existUser·p0.9999: 29.872 ms/op
                 existUser·p1.00:   30.474 ms/op

Iteration   2: 5.188 ±(99.9%) 0.020 ms/op
                 existUser·p0.00:   2.228 ms/op
                 existUser·p0.50:   4.850 ms/op
                 existUser·p0.90:   6.447 ms/op
                 existUser·p0.95:   7.520 ms/op
                 existUser·p0.99:   10.420 ms/op
                 existUser·p0.999:  26.082 ms/op
                 existUser·p0.9999: 33.773 ms/op
                 existUser·p1.00:   34.537 ms/op

Iteration   3: 5.414 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   1.309 ms/op
                 existUser·p0.50:   4.981 ms/op
                 existUser·p0.90:   7.037 ms/op
                 existUser·p0.95:   8.159 ms/op
                 existUser·p0.99:   11.338 ms/op
                 existUser·p0.999:  27.294 ms/op
                 existUser·p0.9999: 33.459 ms/op
                 existUser·p1.00:   37.618 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 179480
  mean =      5.346 ±(99.9%) 0.012 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 66 
    [ 2.500,  5.000) = 92296 
    [ 5.000,  7.500) = 75691 
    [ 7.500, 10.000) = 8624 
    [10.000, 12.500) = 1924 
    [12.500, 15.000) = 496 
    [15.000, 17.500) = 161 
    [17.500, 20.000) = 37 
    [20.000, 22.500) = 5 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 37 
    [27.500, 30.000) = 51 
    [30.000, 32.500) = 41 
    [32.500, 35.000) = 34 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.309 ms/op
     p(50.0000) =      4.964 ms/op
     p(90.0000) =      6.816 ms/op
     p(95.0000) =      7.873 ms/op
     p(99.0000) =     10.879 ms/op
     p(99.9000) =     22.529 ms/op
     p(99.9900) =     33.425 ms/op
     p(99.9990) =     35.169 ms/op
     p(99.9999) =     37.618 ms/op
    p(100.0000) =     37.618 ms/op


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
# Warmup Iteration   1: 18.091 ±(99.9%) 0.303 ms/op
# Warmup Iteration   2: 6.574 ±(99.9%) 0.044 ms/op
# Warmup Iteration   3: 5.442 ±(99.9%) 0.026 ms/op
Iteration   1: 5.820 ±(99.9%) 0.028 ms/op
                 getUser·p0.00:   2.609 ms/op
                 getUser·p0.50:   5.292 ms/op
                 getUser·p0.90:   7.815 ms/op
                 getUser·p0.95:   9.290 ms/op
                 getUser·p0.99:   13.763 ms/op
                 getUser·p0.999:  25.963 ms/op
                 getUser·p0.9999: 32.276 ms/op
                 getUser·p1.00:   33.456 ms/op

Iteration   2: 5.511 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.095 ms/op
                 getUser·p0.50:   5.120 ms/op
                 getUser·p0.90:   6.955 ms/op
                 getUser·p0.95:   8.225 ms/op
                 getUser·p0.99:   11.878 ms/op
                 getUser·p0.999:  25.461 ms/op
                 getUser·p0.9999: 28.900 ms/op
                 getUser·p1.00:   31.228 ms/op

Iteration   3: 5.536 ±(99.9%) 0.019 ms/op
                 getUser·p0.00:   2.449 ms/op
                 getUser·p0.50:   5.259 ms/op
                 getUser·p0.90:   6.783 ms/op
                 getUser·p0.95:   7.782 ms/op
                 getUser·p0.99:   10.551 ms/op
                 getUser·p0.999:  19.271 ms/op
                 getUser·p0.9999: 30.802 ms/op
                 getUser·p1.00:   32.080 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 170721
  mean =      5.619 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 6 
    [ 2.500,  5.000) = 67861 
    [ 5.000,  7.500) = 88568 
    [ 7.500, 10.000) = 10460 
    [10.000, 12.500) = 2386 
    [12.500, 15.000) = 771 
    [15.000, 17.500) = 333 
    [17.500, 20.000) = 114 
    [20.000, 22.500) = 42 
    [22.500, 25.000) = 23 
    [25.000, 27.500) = 60 
    [27.500, 30.000) = 59 
    [30.000, 32.500) = 35 
    [32.500, 35.000) = 3 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      2.095 ms/op
     p(50.0000) =      5.218 ms/op
     p(90.0000) =      7.176 ms/op
     p(95.0000) =      8.438 ms/op
     p(99.0000) =     12.039 ms/op
     p(99.9000) =     23.986 ms/op
     p(99.9900) =     31.457 ms/op
     p(99.9990) =     33.062 ms/op
     p(99.9999) =     33.456 ms/op
    p(100.0000) =     33.456 ms/op


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
# Warmup Iteration   1: 20.670 ±(99.9%) 0.345 ms/op
# Warmup Iteration   2: 8.505 ±(99.9%) 0.069 ms/op
# Warmup Iteration   3: 6.602 ±(99.9%) 0.028 ms/op
Iteration   1: 6.430 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   3.105 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   8.151 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   12.969 ms/op
                 listUser·p0.999:  27.107 ms/op
                 listUser·p0.9999: 29.427 ms/op
                 listUser·p1.00:   29.655 ms/op

Iteration   2: 6.452 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   1.796 ms/op
                 listUser·p0.50:   5.980 ms/op
                 listUser·p0.90:   8.126 ms/op
                 listUser·p0.95:   9.601 ms/op
                 listUser·p0.99:   13.337 ms/op
                 listUser·p0.999:  30.645 ms/op
                 listUser·p0.9999: 34.275 ms/op
                 listUser·p1.00:   34.537 ms/op

Iteration   3: 6.447 ±(99.9%) 0.026 ms/op
                 listUser·p0.00:   2.851 ms/op
                 listUser·p0.50:   6.054 ms/op
                 listUser·p0.90:   8.020 ms/op
                 listUser·p0.95:   9.437 ms/op
                 listUser·p0.99:   13.091 ms/op
                 listUser·p0.999:  27.787 ms/op
                 listUser·p0.9999: 30.806 ms/op
                 listUser·p1.00:   32.211 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 148913
  mean =      6.443 ±(99.9%) 0.016 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 5 
    [ 2.500,  5.000) = 8351 
    [ 5.000,  7.500) = 119366 
    [ 7.500, 10.000) = 15589 
    [10.000, 12.500) = 3649 
    [12.500, 15.000) = 1189 
    [15.000, 17.500) = 342 
    [17.500, 20.000) = 46 
    [20.000, 22.500) = 79 
    [22.500, 25.000) = 46 
    [25.000, 27.500) = 63 
    [27.500, 30.000) = 111 
    [30.000, 32.500) = 59 
    [32.500, 35.000) = 18 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.796 ms/op
     p(50.0000) =      6.013 ms/op
     p(90.0000) =      8.102 ms/op
     p(95.0000) =      9.470 ms/op
     p(99.0000) =     13.173 ms/op
     p(99.9000) =     28.511 ms/op
     p(99.9900) =     32.774 ms/op
     p(99.9990) =     34.505 ms/op
     p(99.9999) =     34.537 ms/op
    p(100.0000) =     34.537 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.708 ± 4.276  ops/ms
ClientPb.existUser                       thrpt       3   6.223 ± 2.582  ops/ms
ClientPb.getUser                         thrpt       3   5.777 ± 4.101  ops/ms
ClientPb.listUser                        thrpt       3   5.144 ± 2.930  ops/ms
ClientPb.createUser                       avgt       3   5.554 ± 2.139   ms/op
ClientPb.existUser                        avgt       3   5.289 ± 1.012   ms/op
ClientPb.getUser                          avgt       3   5.534 ± 2.377   ms/op
ClientPb.listUser                         avgt       3   6.299 ± 2.407   ms/op
ClientPb.createUser                     sample  172073   5.573 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.860           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.136           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.152           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.331           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.911           ms/op
ClientPb.createUser:createUser·p0.999   sample          21.658           ms/op
ClientPb.createUser:createUser·p0.9999  sample          30.402           ms/op
ClientPb.createUser:createUser·p1.00    sample          32.473           ms/op
ClientPb.existUser                      sample  179480   5.346 ± 0.012   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.309           ms/op
ClientPb.existUser:existUser·p0.50      sample           4.964           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.816           ms/op
ClientPb.existUser:existUser·p0.95      sample           7.873           ms/op
ClientPb.existUser:existUser·p0.99      sample          10.879           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.529           ms/op
ClientPb.existUser:existUser·p0.9999    sample          33.425           ms/op
ClientPb.existUser:existUser·p1.00      sample          37.618           ms/op
ClientPb.getUser                        sample  170721   5.619 ± 0.013   ms/op
ClientPb.getUser:getUser·p0.00          sample           2.095           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.218           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.176           ms/op
ClientPb.getUser:getUser·p0.95          sample           8.438           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.039           ms/op
ClientPb.getUser:getUser·p0.999         sample          23.986           ms/op
ClientPb.getUser:getUser·p0.9999        sample          31.457           ms/op
ClientPb.getUser:getUser·p1.00          sample          33.456           ms/op
ClientPb.listUser                       sample  148913   6.443 ± 0.016   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.796           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.013           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.102           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.470           ms/op
ClientPb.listUser:listUser·p0.99        sample          13.173           ms/op
ClientPb.listUser:listUser·p0.999       sample          28.511           ms/op
ClientPb.listUser:listUser·p0.9999      sample          32.774           ms/op
ClientPb.listUser:listUser·p1.00        sample          34.537           ms/op
