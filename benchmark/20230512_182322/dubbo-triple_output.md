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
# Warmup Iteration   1: 2.576 ops/ms
# Warmup Iteration   2: 6.465 ops/ms
# Warmup Iteration   3: 9.206 ops/ms
Iteration   1: 9.754 ops/ms
Iteration   2: 9.674 ops/ms
Iteration   3: 10.069 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  9.832 ±(99.9%) 3.810 ops/ms [Average]
  (min, avg, max) = (9.674, 9.832, 10.069), stdev = 0.209
  CI (99.9%): [6.022, 13.643] (assumes normal distribution)


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

# Run progress: 8.33% complete, ETA 00:12:08
# Fork: 1 of 1
# Warmup Iteration   1: 3.533 ops/ms
# Warmup Iteration   2: 9.341 ops/ms
# Warmup Iteration   3: 10.298 ops/ms
Iteration   1: 10.266 ops/ms
Iteration   2: 10.447 ops/ms
Iteration   3: 10.242 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  10.318 ±(99.9%) 2.040 ops/ms [Average]
  (min, avg, max) = (10.242, 10.318, 10.447), stdev = 0.112
  CI (99.9%): [8.278, 12.358] (assumes normal distribution)


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
# Warmup Iteration   1: 3.864 ops/ms
# Warmup Iteration   2: 9.036 ops/ms
# Warmup Iteration   3: 9.890 ops/ms
Iteration   1: 10.284 ops/ms
Iteration   2: 10.467 ops/ms
Iteration   3: 9.803 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  10.185 ±(99.9%) 6.259 ops/ms [Average]
  (min, avg, max) = (9.803, 10.185, 10.467), stdev = 0.343
  CI (99.9%): [3.926, 16.443] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:54
# Fork: 1 of 1
# Warmup Iteration   1: 3.440 ops/ms
# Warmup Iteration   2: 7.949 ops/ms
# Warmup Iteration   3: 8.611 ops/ms
Iteration   1: 8.428 ops/ms
Iteration   2: 8.624 ops/ms
Iteration   3: 8.754 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  8.602 ±(99.9%) 3.001 ops/ms [Average]
  (min, avg, max) = (8.428, 8.602, 8.754), stdev = 0.165
  CI (99.9%): [5.600, 11.603] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:48
# Fork: 1 of 1
# Warmup Iteration   1: 7.444 ±(99.9%) 0.028 ms/op
# Warmup Iteration   2: 3.411 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 3.343 ±(99.9%) 0.006 ms/op
Iteration   1: 3.087 ±(99.9%) 0.005 ms/op
Iteration   2: 3.140 ±(99.9%) 0.007 ms/op
Iteration   3: 3.093 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.107 ±(99.9%) 0.529 ms/op [Average]
  (min, avg, max) = (3.087, 3.107, 3.140), stdev = 0.029
  CI (99.9%): [2.577, 3.636] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:42
# Fork: 1 of 1
# Warmup Iteration   1: 7.138 ±(99.9%) 0.030 ms/op
# Warmup Iteration   2: 3.206 ±(99.9%) 0.001 ms/op
# Warmup Iteration   3: 3.045 ±(99.9%) 0.001 ms/op
Iteration   1: 3.197 ±(99.9%) 0.005 ms/op
Iteration   2: 2.987 ±(99.9%) 0.008 ms/op
Iteration   3: 3.088 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.091 ±(99.9%) 1.915 ms/op [Average]
  (min, avg, max) = (2.987, 3.091, 3.197), stdev = 0.105
  CI (99.9%): [1.176, 5.005] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:35
# Fork: 1 of 1
# Warmup Iteration   1: 7.783 ±(99.9%) 0.029 ms/op
# Warmup Iteration   2: 3.489 ±(99.9%) 0.002 ms/op
# Warmup Iteration   3: 3.242 ±(99.9%) 0.001 ms/op
Iteration   1: 3.163 ±(99.9%) 0.003 ms/op
Iteration   2: 3.257 ±(99.9%) 0.005 ms/op
Iteration   3: 3.084 ±(99.9%) 0.006 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.168 ±(99.9%) 1.579 ms/op [Average]
  (min, avg, max) = (3.084, 3.168, 3.257), stdev = 0.087
  CI (99.9%): [1.589, 4.746] (assumes normal distribution)


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

# Run progress: 58.33% complete, ETA 00:05:28
# Fork: 1 of 1
# Warmup Iteration   1: 8.333 ±(99.9%) 0.022 ms/op
# Warmup Iteration   2: 3.936 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 3.786 ±(99.9%) 0.004 ms/op
Iteration   1: 3.694 ±(99.9%) 0.006 ms/op
Iteration   2: 3.722 ±(99.9%) 0.006 ms/op
Iteration   3: 3.693 ±(99.9%) 0.009 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  3.703 ±(99.9%) 0.296 ms/op [Average]
  (min, avg, max) = (3.693, 3.703, 3.722), stdev = 0.016
  CI (99.9%): [3.407, 3.999] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:23
# Fork: 1 of 1
# Warmup Iteration   1: 7.314 ±(99.9%) 0.096 ms/op
# Warmup Iteration   2: 3.989 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.201 ±(99.9%) 0.008 ms/op
Iteration   1: 3.105 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   0.994 ms/op
                 createUser·p0.50:   2.970 ms/op
                 createUser·p0.90:   3.420 ms/op
                 createUser·p0.95:   3.658 ms/op
                 createUser·p0.99:   5.382 ms/op
                 createUser·p0.999:  19.399 ms/op
                 createUser·p0.9999: 45.726 ms/op
                 createUser·p1.00:   51.118 ms/op

Iteration   2: 3.213 ±(99.9%) 0.009 ms/op
                 createUser·p0.00:   1.327 ms/op
                 createUser·p0.50:   3.154 ms/op
                 createUser·p0.90:   3.621 ms/op
                 createUser·p0.95:   3.887 ms/op
                 createUser·p0.99:   5.390 ms/op
                 createUser·p0.999:  19.111 ms/op
                 createUser·p0.9999: 23.430 ms/op
                 createUser·p1.00:   24.052 ms/op

Iteration   3: 3.085 ±(99.9%) 0.007 ms/op
                 createUser·p0.00:   0.695 ms/op
                 createUser·p0.50:   3.105 ms/op
                 createUser·p0.90:   3.224 ms/op
                 createUser·p0.95:   3.351 ms/op
                 createUser·p0.99:   4.926 ms/op
                 createUser·p0.999:  16.908 ms/op
                 createUser·p0.9999: 21.156 ms/op
                 createUser·p1.00:   21.856 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 305946
  mean =      3.134 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 301746 
    [ 5.000, 10.000) = 3672 
    [10.000, 15.000) = 105 
    [15.000, 20.000) = 254 
    [20.000, 25.000) = 134 
    [25.000, 30.000) = 0 
    [30.000, 35.000) = 1 
    [35.000, 40.000) = 2 
    [40.000, 45.000) = 10 
    [45.000, 50.000) = 21 
    [50.000, 55.000) = 1 

  Percentiles, ms/op:
      p(0.0000) =      0.695 ms/op
     p(50.0000) =      3.076 ms/op
     p(90.0000) =      3.453 ms/op
     p(95.0000) =      3.711 ms/op
     p(99.0000) =      5.267 ms/op
     p(99.9000) =     18.383 ms/op
     p(99.9900) =     44.788 ms/op
     p(99.9990) =     45.806 ms/op
     p(99.9999) =     51.118 ms/op
    p(100.0000) =     51.118 ms/op


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

# Run progress: 75.00% complete, ETA 00:03:17
# Fork: 1 of 1
# Warmup Iteration   1: 6.827 ±(99.9%) 0.079 ms/op
# Warmup Iteration   2: 3.330 ±(99.9%) 0.012 ms/op
# Warmup Iteration   3: 3.059 ±(99.9%) 0.008 ms/op
Iteration   1: 3.048 ±(99.9%) 0.007 ms/op
                 existUser·p0.00:   1.143 ms/op
                 existUser·p0.50:   3.023 ms/op
                 existUser·p0.90:   3.277 ms/op
                 existUser·p0.95:   3.531 ms/op
                 existUser·p0.99:   5.194 ms/op
                 existUser·p0.999:  10.434 ms/op
                 existUser·p0.9999: 21.709 ms/op
                 existUser·p1.00:   22.807 ms/op

Iteration   2: 3.034 ±(99.9%) 0.008 ms/op
                 existUser·p0.00:   1.612 ms/op
                 existUser·p0.50:   2.929 ms/op
                 existUser·p0.90:   3.269 ms/op
                 existUser·p0.95:   3.498 ms/op
                 existUser·p0.99:   5.620 ms/op
                 existUser·p0.999:  10.043 ms/op
                 existUser·p0.9999: 22.639 ms/op
                 existUser·p1.00:   23.265 ms/op

Iteration   3: 3.060 ±(99.9%) 0.006 ms/op
                 existUser·p0.00:   0.748 ms/op
                 existUser·p0.50:   2.970 ms/op
                 existUser·p0.90:   3.322 ms/op
                 existUser·p0.95:   3.514 ms/op
                 existUser·p0.99:   5.488 ms/op
                 existUser·p0.999:  9.667 ms/op
                 existUser·p0.9999: 20.138 ms/op
                 existUser·p1.00:   20.906 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 315104
  mean =      3.047 ±(99.9%) 0.004 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 14684 
    [ 2.500,  5.000) = 295694 
    [ 5.000,  7.500) = 3965 
    [ 7.500, 10.000) = 438 
    [10.000, 12.500) = 35 
    [12.500, 15.000) = 43 
    [15.000, 17.500) = 22 
    [17.500, 20.000) = 67 
    [20.000, 22.500) = 134 
    [22.500, 25.000) = 22 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      0.748 ms/op
     p(50.0000) =      2.970 ms/op
     p(90.0000) =      3.293 ms/op
     p(95.0000) =      3.514 ms/op
     p(99.0000) =      5.407 ms/op
     p(99.9000) =     10.011 ms/op
     p(99.9900) =     22.315 ms/op
     p(99.9990) =     23.054 ms/op
     p(99.9999) =     23.265 ms/op
    p(100.0000) =     23.265 ms/op


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

# Run progress: 83.33% complete, ETA 00:02:11
# Fork: 1 of 1
# Warmup Iteration   1: 7.600 ±(99.9%) 0.089 ms/op
# Warmup Iteration   2: 3.348 ±(99.9%) 0.011 ms/op
# Warmup Iteration   3: 3.259 ±(99.9%) 0.009 ms/op
Iteration   1: 3.124 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   0.669 ms/op
                 getUser·p0.50:   2.998 ms/op
                 getUser·p0.90:   3.375 ms/op
                 getUser·p0.95:   3.568 ms/op
                 getUser·p0.99:   5.980 ms/op
                 getUser·p0.999:  15.745 ms/op
                 getUser·p0.9999: 20.964 ms/op
                 getUser·p1.00:   21.725 ms/op

Iteration   2: 3.209 ±(99.9%) 0.008 ms/op
                 getUser·p0.00:   1.061 ms/op
                 getUser·p0.50:   3.125 ms/op
                 getUser·p0.90:   3.641 ms/op
                 getUser·p0.95:   3.973 ms/op
                 getUser·p0.99:   5.325 ms/op
                 getUser·p0.999:  8.952 ms/op
                 getUser·p0.9999: 27.265 ms/op
                 getUser·p1.00:   28.312 ms/op

Iteration   3: 3.326 ±(99.9%) 0.009 ms/op
                 getUser·p0.00:   0.825 ms/op
                 getUser·p0.50:   3.207 ms/op
                 getUser·p0.90:   3.887 ms/op
                 getUser·p0.95:   4.743 ms/op
                 getUser·p0.99:   6.332 ms/op
                 getUser·p0.999:  14.294 ms/op
                 getUser·p0.9999: 20.341 ms/op
                 getUser·p1.00:   21.758 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 298206
  mean =      3.218 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 16999 
    [ 2.500,  5.000) = 272034 
    [ 5.000,  7.500) = 8149 
    [ 7.500, 10.000) = 675 
    [10.000, 12.500) = 38 
    [12.500, 15.000) = 12 
    [15.000, 17.500) = 43 
    [17.500, 20.000) = 104 
    [20.000, 22.500) = 120 
    [22.500, 25.000) = 0 
    [25.000, 27.500) = 28 

  Percentiles, ms/op:
      p(0.0000) =      0.669 ms/op
     p(50.0000) =      3.117 ms/op
     p(90.0000) =      3.629 ms/op
     p(95.0000) =      4.096 ms/op
     p(99.0000) =      6.070 ms/op
     p(99.9000) =     15.070 ms/op
     p(99.9900) =     25.315 ms/op
     p(99.9990) =     28.050 ms/op
     p(99.9999) =     28.312 ms/op
    p(100.0000) =     28.312 ms/op


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

# Run progress: 91.67% complete, ETA 00:01:05
# Fork: 1 of 1
# Warmup Iteration   1: 9.263 ±(99.9%) 0.128 ms/op
# Warmup Iteration   2: 4.150 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 3.765 ±(99.9%) 0.011 ms/op
Iteration   1: 3.684 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   1.473 ms/op
                 listUser·p0.50:   3.584 ms/op
                 listUser·p0.90:   3.912 ms/op
                 listUser·p0.95:   4.227 ms/op
                 listUser·p0.99:   6.971 ms/op
                 listUser·p0.999:  15.139 ms/op
                 listUser·p0.9999: 22.030 ms/op
                 listUser·p1.00:   22.872 ms/op

Iteration   2: 3.865 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.228 ms/op
                 listUser·p0.50:   3.707 ms/op
                 listUser·p0.90:   4.375 ms/op
                 listUser·p0.95:   4.653 ms/op
                 listUser·p0.99:   7.258 ms/op
                 listUser·p0.999:  13.669 ms/op
                 listUser·p0.9999: 18.776 ms/op
                 listUser·p1.00:   18.874 ms/op

Iteration   3: 3.726 ±(99.9%) 0.009 ms/op
                 listUser·p0.00:   2.179 ms/op
                 listUser·p0.50:   3.559 ms/op
                 listUser·p0.90:   4.055 ms/op
                 listUser·p0.95:   4.334 ms/op
                 listUser·p0.99:   7.078 ms/op
                 listUser·p0.999:  13.418 ms/op
                 listUser·p0.9999: 14.893 ms/op
                 listUser·p1.00:   15.008 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 255450
  mean =      3.757 ±(99.9%) 0.005 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 71 
    [ 2.500,  5.000) = 247021 
    [ 5.000,  7.500) = 6340 
    [ 7.500, 10.000) = 1322 
    [10.000, 12.500) = 211 
    [12.500, 15.000) = 353 
    [15.000, 17.500) = 55 
    [17.500, 20.000) = 43 
    [20.000, 22.500) = 33 
    [22.500, 25.000) = 1 
    [25.000, 27.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.473 ms/op
     p(50.0000) =      3.625 ms/op
     p(90.0000) =      4.182 ms/op
     p(95.0000) =      4.481 ms/op
     p(99.0000) =      7.062 ms/op
     p(99.9000) =     13.853 ms/op
     p(99.9900) =     20.414 ms/op
     p(99.9990) =     22.264 ms/op
     p(99.9999) =     22.872 ms/op
    p(100.0000) =     22.872 ms/op


# Run complete. Total time: 00:13:10

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   9.832 ± 3.810  ops/ms
ClientPb.existUser                       thrpt       3  10.318 ± 2.040  ops/ms
ClientPb.getUser                         thrpt       3  10.185 ± 6.259  ops/ms
ClientPb.listUser                        thrpt       3   8.602 ± 3.001  ops/ms
ClientPb.createUser                       avgt       3   3.107 ± 0.529   ms/op
ClientPb.existUser                        avgt       3   3.091 ± 1.915   ms/op
ClientPb.getUser                          avgt       3   3.168 ± 1.579   ms/op
ClientPb.listUser                         avgt       3   3.703 ± 0.296   ms/op
ClientPb.createUser                     sample  305946   3.134 ± 0.005   ms/op
ClientPb.createUser:createUser·p0.00    sample           0.695           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.076           ms/op
ClientPb.createUser:createUser·p0.90    sample           3.453           ms/op
ClientPb.createUser:createUser·p0.95    sample           3.711           ms/op
ClientPb.createUser:createUser·p0.99    sample           5.267           ms/op
ClientPb.createUser:createUser·p0.999   sample          18.383           ms/op
ClientPb.createUser:createUser·p0.9999  sample          44.788           ms/op
ClientPb.createUser:createUser·p1.00    sample          51.118           ms/op
ClientPb.existUser                      sample  315104   3.047 ± 0.004   ms/op
ClientPb.existUser:existUser·p0.00      sample           0.748           ms/op
ClientPb.existUser:existUser·p0.50      sample           2.970           ms/op
ClientPb.existUser:existUser·p0.90      sample           3.293           ms/op
ClientPb.existUser:existUser·p0.95      sample           3.514           ms/op
ClientPb.existUser:existUser·p0.99      sample           5.407           ms/op
ClientPb.existUser:existUser·p0.999     sample          10.011           ms/op
ClientPb.existUser:existUser·p0.9999    sample          22.315           ms/op
ClientPb.existUser:existUser·p1.00      sample          23.265           ms/op
ClientPb.getUser                        sample  298206   3.218 ± 0.005   ms/op
ClientPb.getUser:getUser·p0.00          sample           0.669           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.117           ms/op
ClientPb.getUser:getUser·p0.90          sample           3.629           ms/op
ClientPb.getUser:getUser·p0.95          sample           4.096           ms/op
ClientPb.getUser:getUser·p0.99          sample           6.070           ms/op
ClientPb.getUser:getUser·p0.999         sample          15.070           ms/op
ClientPb.getUser:getUser·p0.9999        sample          25.315           ms/op
ClientPb.getUser:getUser·p1.00          sample          28.312           ms/op
ClientPb.listUser                       sample  255450   3.757 ± 0.005   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.473           ms/op
ClientPb.listUser:listUser·p0.50        sample           3.625           ms/op
ClientPb.listUser:listUser·p0.90        sample           4.182           ms/op
ClientPb.listUser:listUser·p0.95        sample           4.481           ms/op
ClientPb.listUser:listUser·p0.99        sample           7.062           ms/op
ClientPb.listUser:listUser·p0.999       sample          13.853           ms/op
ClientPb.listUser:listUser·p0.9999      sample          20.414           ms/op
ClientPb.listUser:listUser·p1.00        sample          22.872           ms/op
