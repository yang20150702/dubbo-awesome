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
# Warmup Iteration   1: 1.011 ops/ms
# Warmup Iteration   2: 2.381 ops/ms
# Warmup Iteration   3: 4.770 ops/ms
Iteration   1: 5.264 ops/ms
Iteration   2: 5.470 ops/ms
Iteration   3: 5.567 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.433 ±(99.9%) 2.824 ops/ms [Average]
  (min, avg, max) = (5.264, 5.433, 5.567), stdev = 0.155
  CI (99.9%): [2.610, 8.257] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:05
# Fork: 1 of 1
# Warmup Iteration   1: 1.543 ops/ms
# Warmup Iteration   2: 4.466 ops/ms
# Warmup Iteration   3: 5.735 ops/ms
Iteration   1: 5.871 ops/ms
Iteration   2: 5.966 ops/ms
Iteration   3: 5.870 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.902 ±(99.9%) 1.013 ops/ms [Average]
  (min, avg, max) = (5.870, 5.902, 5.966), stdev = 0.056
  CI (99.9%): [4.889, 6.915] (assumes normal distribution)


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
# Warmup Iteration   1: 1.394 ops/ms
# Warmup Iteration   2: 3.794 ops/ms
# Warmup Iteration   3: 5.329 ops/ms
Iteration   1: 5.680 ops/ms
Iteration   2: 5.563 ops/ms
Iteration   3: 5.625 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.622 ±(99.9%) 1.066 ops/ms [Average]
  (min, avg, max) = (5.563, 5.622, 5.680), stdev = 0.058
  CI (99.9%): [4.557, 6.688] (assumes normal distribution)


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
# Warmup Iteration   1: 1.337 ops/ms
# Warmup Iteration   2: 3.531 ops/ms
# Warmup Iteration   3: 4.699 ops/ms
Iteration   1: 4.836 ops/ms
Iteration   2: 4.759 ops/ms
Iteration   3: 4.936 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.844 ±(99.9%) 1.619 ops/ms [Average]
  (min, avg, max) = (4.759, 4.844, 4.936), stdev = 0.089
  CI (99.9%): [3.224, 6.463] (assumes normal distribution)


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
# Warmup Iteration   1: 18.291 ±(99.9%) 0.117 ms/op
# Warmup Iteration   2: 6.611 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 5.862 ±(99.9%) 0.016 ms/op
Iteration   1: 5.443 ±(99.9%) 0.014 ms/op
Iteration   2: 5.440 ±(99.9%) 0.016 ms/op
Iteration   3: 5.609 ±(99.9%) 0.010 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  5.497 ±(99.9%) 1.772 ms/op [Average]
  (min, avg, max) = (5.440, 5.497, 5.609), stdev = 0.097
  CI (99.9%): [3.726, 7.269] (assumes normal distribution)


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
# Warmup Iteration   1: 17.683 ±(99.9%) 0.087 ms/op
# Warmup Iteration   2: 7.938 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.605 ±(99.9%) 0.008 ms/op
Iteration   1: 5.575 ±(99.9%) 0.013 ms/op
Iteration   2: 5.238 ±(99.9%) 0.016 ms/op
Iteration   3: 5.163 ±(99.9%) 0.018 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  5.326 ±(99.9%) 4.004 ms/op [Average]
  (min, avg, max) = (5.163, 5.326, 5.575), stdev = 0.219
  CI (99.9%): [1.322, 9.329] (assumes normal distribution)


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
# Warmup Iteration   1: 16.926 ±(99.9%) 0.072 ms/op
# Warmup Iteration   2: 6.274 ±(99.9%) 0.013 ms/op
# Warmup Iteration   3: 5.680 ±(99.9%) 0.009 ms/op
Iteration   1: 5.826 ±(99.9%) 0.013 ms/op
Iteration   2: 5.534 ±(99.9%) 0.023 ms/op
Iteration   3: 5.628 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  5.663 ±(99.9%) 2.719 ms/op [Average]
  (min, avg, max) = (5.534, 5.663, 5.826), stdev = 0.149
  CI (99.9%): [2.943, 8.382] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:30
# Fork: 1 of 1
# Warmup Iteration   1: 20.348 ±(99.9%) 0.107 ms/op
# Warmup Iteration   2: 8.367 ±(99.9%) 0.010 ms/op
# Warmup Iteration   3: 6.908 ±(99.9%) 0.012 ms/op
Iteration   1: 6.704 ±(99.9%) 0.016 ms/op
Iteration   2: 6.733 ±(99.9%) 0.020 ms/op
Iteration   3: 6.570 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.669 ±(99.9%) 1.589 ms/op [Average]
  (min, avg, max) = (6.570, 6.669, 6.733), stdev = 0.087
  CI (99.9%): [5.080, 8.259] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:24
# Fork: 1 of 1
# Warmup Iteration   1: 17.172 ±(99.9%) 0.254 ms/op
# Warmup Iteration   2: 7.552 ±(99.9%) 0.050 ms/op
# Warmup Iteration   3: 6.230 ±(99.9%) 0.028 ms/op
Iteration   1: 5.748 ±(99.9%) 0.019 ms/op
                 createUser·p0.00:   2.437 ms/op
                 createUser·p0.50:   5.431 ms/op
                 createUser·p0.90:   7.193 ms/op
                 createUser·p0.95:   8.061 ms/op
                 createUser·p0.99:   10.633 ms/op
                 createUser·p0.999:  16.857 ms/op
                 createUser·p0.9999: 28.785 ms/op
                 createUser·p1.00:   28.803 ms/op

Iteration   2: 5.761 ±(99.9%) 0.024 ms/op
                 createUser·p0.00:   2.630 ms/op
                 createUser·p0.50:   5.358 ms/op
                 createUser·p0.90:   7.193 ms/op
                 createUser·p0.95:   8.282 ms/op
                 createUser·p0.99:   12.042 ms/op
                 createUser·p0.999:  27.977 ms/op
                 createUser·p0.9999: 33.104 ms/op
                 createUser·p1.00:   35.062 ms/op

Iteration   3: 5.624 ±(99.9%) 0.022 ms/op
                 createUser·p0.00:   2.392 ms/op
                 createUser·p0.50:   5.235 ms/op
                 createUser·p0.90:   6.906 ms/op
                 createUser·p0.95:   8.045 ms/op
                 createUser·p0.99:   11.559 ms/op
                 createUser·p0.999:  28.425 ms/op
                 createUser·p0.9999: 32.320 ms/op
                 createUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 167885
  mean =      5.710 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 4 
    [ 2.500,  5.000) = 50932 
    [ 5.000,  7.500) = 104757 
    [ 7.500, 10.000) = 9071 
    [10.000, 12.500) = 2049 
    [12.500, 15.000) = 552 
    [15.000, 17.500) = 250 
    [17.500, 20.000) = 34 
    [20.000, 22.500) = 32 
    [22.500, 25.000) = 31 
    [25.000, 27.500) = 42 
    [27.500, 30.000) = 73 
    [30.000, 32.500) = 47 
    [32.500, 35.000) = 10 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      2.392 ms/op
     p(50.0000) =      5.341 ms/op
     p(90.0000) =      7.102 ms/op
     p(95.0000) =      8.135 ms/op
     p(99.0000) =     11.354 ms/op
     p(99.9000) =     25.501 ms/op
     p(99.9900) =     32.309 ms/op
     p(99.9990) =     35.017 ms/op
     p(99.9999) =     35.062 ms/op
    p(100.0000) =     35.062 ms/op


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
# Warmup Iteration   1: 16.655 ±(99.9%) 0.273 ms/op
# Warmup Iteration   2: 6.731 ±(99.9%) 0.041 ms/op
# Warmup Iteration   3: 5.715 ±(99.9%) 0.023 ms/op
Iteration   1: 5.676 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.011 ms/op
                 existUser·p0.50:   5.415 ms/op
                 existUser·p0.90:   7.152 ms/op
                 existUser·p0.95:   8.847 ms/op
                 existUser·p0.99:   11.387 ms/op
                 existUser·p0.999:  15.395 ms/op
                 existUser·p0.9999: 30.025 ms/op
                 existUser·p1.00:   31.130 ms/op

Iteration   2: 5.578 ±(99.9%) 0.023 ms/op
                 existUser·p0.00:   2.658 ms/op
                 existUser·p0.50:   5.276 ms/op
                 existUser·p0.90:   6.750 ms/op
                 existUser·p0.95:   8.077 ms/op
                 existUser·p0.99:   12.222 ms/op
                 existUser·p0.999:  28.523 ms/op
                 existUser·p0.9999: 31.821 ms/op
                 existUser·p1.00:   33.194 ms/op

Iteration   3: 5.624 ±(99.9%) 0.022 ms/op
                 existUser·p0.00:   1.473 ms/op
                 existUser·p0.50:   5.349 ms/op
                 existUser·p0.90:   6.767 ms/op
                 existUser·p0.95:   7.815 ms/op
                 existUser·p0.99:   11.311 ms/op
                 existUser·p0.999:  29.954 ms/op
                 existUser·p0.9999: 33.147 ms/op
                 existUser·p1.00:   33.882 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 170582
  mean =      5.625 ±(99.9%) 0.013 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 13 
    [ 2.500,  5.000) = 49295 
    [ 5.000,  7.500) = 109469 
    [ 7.500, 10.000) = 8037 
    [10.000, 12.500) = 2598 
    [12.500, 15.000) = 647 
    [15.000, 17.500) = 266 
    [17.500, 20.000) = 76 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 16 
    [25.000, 27.500) = 16 
    [27.500, 30.000) = 52 
    [30.000, 32.500) = 78 
    [32.500, 35.000) = 19 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.011 ms/op
     p(50.0000) =      5.349 ms/op
     p(90.0000) =      6.881 ms/op
     p(95.0000) =      8.200 ms/op
     p(99.0000) =     11.600 ms/op
     p(99.9000) =     23.579 ms/op
     p(99.9900) =     32.602 ms/op
     p(99.9990) =     33.743 ms/op
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
# Benchmark: org.apache.dubbo.benchmark.ClientPb.getUser

# Run progress: 83.33% complete, ETA 00:02:12
# Fork: 1 of 1
# Warmup Iteration   1: 18.187 ±(99.9%) 0.300 ms/op
# Warmup Iteration   2: 6.781 ±(99.9%) 0.042 ms/op
# Warmup Iteration   3: 6.064 ±(99.9%) 0.029 ms/op
Iteration   1: 6.207 ±(99.9%) 0.029 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   5.661 ms/op
                 getUser·p0.90:   8.389 ms/op
                 getUser·p0.95:   9.830 ms/op
                 getUser·p0.99:   13.783 ms/op
                 getUser·p0.999:  24.445 ms/op
                 getUser·p0.9999: 27.515 ms/op
                 getUser·p1.00:   28.639 ms/op

Iteration   2: 6.176 ±(99.9%) 0.026 ms/op
                 getUser·p0.00:   2.925 ms/op
                 getUser·p0.50:   5.751 ms/op
                 getUser·p0.90:   7.913 ms/op
                 getUser·p0.95:   9.421 ms/op
                 getUser·p0.99:   12.239 ms/op
                 getUser·p0.999:  29.055 ms/op
                 getUser·p0.9999: 33.377 ms/op
                 getUser·p1.00:   33.817 ms/op

Iteration   3: 5.830 ±(99.9%) 0.022 ms/op
                 getUser·p0.00:   2.826 ms/op
                 getUser·p0.50:   5.530 ms/op
                 getUser·p0.90:   7.021 ms/op
                 getUser·p0.95:   7.987 ms/op
                 getUser·p0.99:   10.994 ms/op
                 getUser·p0.999:  30.454 ms/op
                 getUser·p0.9999: 33.751 ms/op
                 getUser·p1.00:   34.341 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 158216
  mean =      6.066 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 7 
    [ 2.500,  5.000) = 29420 
    [ 5.000,  7.500) = 110587 
    [ 7.500, 10.000) = 13056 
    [10.000, 12.500) = 3590 
    [12.500, 15.000) = 826 
    [15.000, 17.500) = 322 
    [17.500, 20.000) = 131 
    [20.000, 22.500) = 62 
    [22.500, 25.000) = 52 
    [25.000, 27.500) = 30 
    [27.500, 30.000) = 31 
    [30.000, 32.500) = 73 
    [32.500, 35.000) = 29 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.937 ms/op
     p(50.0000) =      5.628 ms/op
     p(90.0000) =      7.758 ms/op
     p(95.0000) =      9.224 ms/op
     p(99.0000) =     12.416 ms/op
     p(99.9000) =     26.193 ms/op
     p(99.9900) =     33.194 ms/op
     p(99.9990) =     34.341 ms/op
     p(99.9999) =     34.341 ms/op
    p(100.0000) =     34.341 ms/op


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
# Warmup Iteration   1: 21.392 ±(99.9%) 0.394 ms/op
# Warmup Iteration   2: 8.792 ±(99.9%) 0.066 ms/op
# Warmup Iteration   3: 6.889 ±(99.9%) 0.032 ms/op
Iteration   1: 6.653 ±(99.9%) 0.028 ms/op
                 listUser·p0.00:   0.553 ms/op
                 listUser·p0.50:   6.144 ms/op
                 listUser·p0.90:   8.364 ms/op
                 listUser·p0.95:   9.814 ms/op
                 listUser·p0.99:   13.353 ms/op
                 listUser·p0.999:  27.320 ms/op
                 listUser·p0.9999: 35.599 ms/op
                 listUser·p1.00:   36.045 ms/op

Iteration   2: 6.477 ±(99.9%) 0.024 ms/op
                 listUser·p0.00:   3.539 ms/op
                 listUser·p0.50:   6.046 ms/op
                 listUser·p0.90:   7.938 ms/op
                 listUser·p0.95:   8.913 ms/op
                 listUser·p0.99:   12.320 ms/op
                 listUser·p0.999:  27.283 ms/op
                 listUser·p0.9999: 30.415 ms/op
                 listUser·p1.00:   30.736 ms/op

Iteration   3: 6.714 ±(99.9%) 0.027 ms/op
                 listUser·p0.00:   2.001 ms/op
                 listUser·p0.50:   6.349 ms/op
                 listUser·p0.90:   8.012 ms/op
                 listUser·p0.95:   9.372 ms/op
                 listUser·p0.99:   13.046 ms/op
                 listUser·p0.999:  30.004 ms/op
                 listUser·p0.9999: 40.123 ms/op
                 listUser·p1.00:   40.763 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 145141
  mean =      6.613 ±(99.9%) 0.015 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 4305 
    [ 5.000, 10.000) = 135591 
    [10.000, 15.000) = 4573 
    [15.000, 20.000) = 367 
    [20.000, 25.000) = 54 
    [25.000, 30.000) = 158 
    [30.000, 35.000) = 55 
    [35.000, 40.000) = 33 
    [40.000, 45.000) = 5 

  Percentiles, ms/op:
      p(0.0000) =      0.553 ms/op
     p(50.0000) =      6.177 ms/op
     p(90.0000) =      8.086 ms/op
     p(95.0000) =      9.372 ms/op
     p(99.0000) =     12.943 ms/op
     p(99.9000) =     27.787 ms/op
     p(99.9900) =     39.157 ms/op
     p(99.9990) =     40.615 ms/op
     p(99.9999) =     40.763 ms/op
    p(100.0000) =     40.763 ms/op


# Run complete. Total time: 00:13:16

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   5.433 ± 2.824  ops/ms
ClientPb.existUser                       thrpt       3   5.902 ± 1.013  ops/ms
ClientPb.getUser                         thrpt       3   5.622 ± 1.066  ops/ms
ClientPb.listUser                        thrpt       3   4.844 ± 1.619  ops/ms
ClientPb.createUser                       avgt       3   5.497 ± 1.772   ms/op
ClientPb.existUser                        avgt       3   5.326 ± 4.004   ms/op
ClientPb.getUser                          avgt       3   5.663 ± 2.719   ms/op
ClientPb.listUser                         avgt       3   6.669 ± 1.589   ms/op
ClientPb.createUser                     sample  167885   5.710 ± 0.013   ms/op
ClientPb.createUser:createUser·p0.00    sample           2.392           ms/op
ClientPb.createUser:createUser·p0.50    sample           5.341           ms/op
ClientPb.createUser:createUser·p0.90    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.95    sample           8.135           ms/op
ClientPb.createUser:createUser·p0.99    sample          11.354           ms/op
ClientPb.createUser:createUser·p0.999   sample          25.501           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.309           ms/op
ClientPb.createUser:createUser·p1.00    sample          35.062           ms/op
ClientPb.existUser                      sample  170582   5.625 ± 0.013   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.011           ms/op
ClientPb.existUser:existUser·p0.50      sample           5.349           ms/op
ClientPb.existUser:existUser·p0.90      sample           6.881           ms/op
ClientPb.existUser:existUser·p0.95      sample           8.200           ms/op
ClientPb.existUser:existUser·p0.99      sample          11.600           ms/op
ClientPb.existUser:existUser·p0.999     sample          23.579           ms/op
ClientPb.existUser:existUser·p0.9999    sample          32.602           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.882           ms/op
ClientPb.getUser                        sample  158216   6.066 ± 0.015   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.937           ms/op
ClientPb.getUser:getUser·p0.50          sample           5.628           ms/op
ClientPb.getUser:getUser·p0.90          sample           7.758           ms/op
ClientPb.getUser:getUser·p0.95          sample           9.224           ms/op
ClientPb.getUser:getUser·p0.99          sample          12.416           ms/op
ClientPb.getUser:getUser·p0.999         sample          26.193           ms/op
ClientPb.getUser:getUser·p0.9999        sample          33.194           ms/op
ClientPb.getUser:getUser·p1.00          sample          34.341           ms/op
ClientPb.listUser                       sample  145141   6.613 ± 0.015   ms/op
ClientPb.listUser:listUser·p0.00        sample           0.553           ms/op
ClientPb.listUser:listUser·p0.50        sample           6.177           ms/op
ClientPb.listUser:listUser·p0.90        sample           8.086           ms/op
ClientPb.listUser:listUser·p0.95        sample           9.372           ms/op
ClientPb.listUser:listUser·p0.99        sample          12.943           ms/op
ClientPb.listUser:listUser·p0.999       sample          27.787           ms/op
ClientPb.listUser:listUser·p0.9999      sample          39.157           ms/op
ClientPb.listUser:listUser·p1.00        sample          40.763           ms/op
