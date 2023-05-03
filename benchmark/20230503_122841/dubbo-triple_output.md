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
# Warmup Iteration   1: 1.528 ops/ms
# Warmup Iteration   2: 3.337 ops/ms
# Warmup Iteration   3: 6.971 ops/ms
Iteration   1: 7.462 ops/ms
Iteration   2: 7.906 ops/ms
Iteration   3: 7.793 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.720 ±(99.9%) 4.215 ops/ms [Average]
  (min, avg, max) = (7.462, 7.720, 7.906), stdev = 0.231
  CI (99.9%): [3.505, 11.936] (assumes normal distribution)


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
# Warmup Iteration   1: 2.283 ops/ms
# Warmup Iteration   2: 6.150 ops/ms
# Warmup Iteration   3: 8.109 ops/ms
Iteration   1: 8.448 ops/ms
Iteration   2: 8.626 ops/ms
Iteration   3: 8.557 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.544 ±(99.9%) 1.640 ops/ms [Average]
  (min, avg, max) = (8.448, 8.544, 8.626), stdev = 0.090
  CI (99.9%): [6.904, 10.184] (assumes normal distribution)


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
# Warmup Iteration   1: 2.041 ops/ms
# Warmup Iteration   2: 5.197 ops/ms
# Warmup Iteration   3: 7.716 ops/ms
Iteration   1: 7.876 ops/ms
Iteration   2: 8.047 ops/ms
Iteration   3: 7.907 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.943 ±(99.9%) 1.659 ops/ms [Average]
  (min, avg, max) = (7.876, 7.943, 8.047), stdev = 0.091
  CI (99.9%): [6.284, 9.602] (assumes normal distribution)


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

# Run progress: 25.00% complete, ETA 00:09:53
# Fork: 1 of 1
# Warmup Iteration   1: 1.959 ops/ms
# Warmup Iteration   2: 5.882 ops/ms
# Warmup Iteration   3: 6.754 ops/ms
Iteration   1: 6.777 ops/ms
Iteration   2: 6.822 ops/ms
Iteration   3: 7.011 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.870 ±(99.9%) 2.264 ops/ms [Average]
  (min, avg, max) = (6.777, 6.870, 7.011), stdev = 0.124
  CI (99.9%): [4.606, 9.134] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.652 ±(99.9%) 0.061 ms/op
# Warmup Iteration   2: 4.640 ±(99.9%) 0.003 ms/op
# Warmup Iteration   3: 4.188 ±(99.9%) 0.004 ms/op
Iteration   1: 4.080 ±(99.9%) 0.006 ms/op
Iteration   2: 3.953 ±(99.9%) 0.003 ms/op
Iteration   3: 4.066 ±(99.9%) 0.004 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  4.033 ±(99.9%) 1.271 ms/op [Average]
  (min, avg, max) = (3.953, 4.033, 4.080), stdev = 0.070
  CI (99.9%): [2.762, 5.303] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:40
# Fork: 1 of 1
# Warmup Iteration   1: 12.125 ±(99.9%) 0.054 ms/op
# Warmup Iteration   2: 4.429 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.851 ±(99.9%) 0.004 ms/op
Iteration   1: 3.904 ±(99.9%) 0.005 ms/op
Iteration   2: 3.812 ±(99.9%) 0.011 ms/op
Iteration   3: 3.743 ±(99.9%) 0.005 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.820 ±(99.9%) 1.479 ms/op [Average]
  (min, avg, max) = (3.743, 3.820, 3.904), stdev = 0.081
  CI (99.9%): [2.340, 5.299] (assumes normal distribution)


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

# Run progress: 50.00% complete, ETA 00:06:34
# Fork: 1 of 1
# Warmup Iteration   1: 12.872 ±(99.9%) 0.060 ms/op
# Warmup Iteration   2: 4.511 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.096 ±(99.9%) 0.008 ms/op
Iteration   1: 3.964 ±(99.9%) 0.009 ms/op
Iteration   2: 3.997 ±(99.9%) 0.008 ms/op
Iteration   3: 3.920 ±(99.9%) 0.007 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.960 ±(99.9%) 0.703 ms/op [Average]
  (min, avg, max) = (3.920, 3.960, 3.997), stdev = 0.039
  CI (99.9%): [3.258, 4.663] (assumes normal distribution)


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
# Warmup Iteration   1: 15.740 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 5.849 ±(99.9%) 0.008 ms/op
# Warmup Iteration   3: 4.765 ±(99.9%) 0.008 ms/op
Iteration   1: 4.605 ±(99.9%) 0.012 ms/op
Iteration   2: 4.530 ±(99.9%) 0.010 ms/op
Iteration   3: 4.687 ±(99.9%) 0.017 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.607 ±(99.9%) 1.436 ms/op [Average]
  (min, avg, max) = (4.530, 4.607, 4.687), stdev = 0.079
  CI (99.9%): [3.171, 6.044] (assumes normal distribution)


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

# Run progress: 66.67% complete, ETA 00:04:22
# Fork: 1 of 1
# Warmup Iteration   1: 11.742 ±(99.9%) 0.180 ms/op
# Warmup Iteration   2: 4.996 ±(99.9%) 0.027 ms/op
# Warmup Iteration   3: 4.303 ±(99.9%) 0.017 ms/op
Iteration   1: 4.096 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.104 ms/op
                 createUser·p0.50:   3.797 ms/op
                 createUser·p0.90:   4.923 ms/op
                 createUser·p0.95:   5.710 ms/op
                 createUser·p0.99:   8.414 ms/op
                 createUser·p0.999:  24.145 ms/op
                 createUser·p0.9999: 26.417 ms/op
                 createUser·p1.00:   34.406 ms/op

Iteration   2: 3.868 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.880 ms/op
                 createUser·p0.50:   3.723 ms/op
                 createUser·p0.90:   4.383 ms/op
                 createUser·p0.95:   4.710 ms/op
                 createUser·p0.99:   6.521 ms/op
                 createUser·p0.999:  25.297 ms/op
                 createUser·p0.9999: 28.836 ms/op
                 createUser·p1.00:   29.327 ms/op

Iteration   3: 3.775 ±(99.9%) 0.010 ms/op
                 createUser·p0.00:   1.106 ms/op
                 createUser·p0.50:   3.768 ms/op
                 createUser·p0.90:   3.940 ms/op
                 createUser·p0.95:   4.202 ms/op
                 createUser·p0.99:   6.341 ms/op
                 createUser·p0.999:  10.257 ms/op
                 createUser·p0.9999: 32.326 ms/op
                 createUser·p1.00:   33.227 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 245699
  mean =      3.908 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 281 
    [ 2.500,  5.000) = 233811 
    [ 5.000,  7.500) = 9700 
    [ 7.500, 10.000) = 1410 
    [10.000, 12.500) = 213 
    [12.500, 15.000) = 28 
    [15.000, 17.500) = 0 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 54 
    [25.000, 27.500) = 97 
    [27.500, 30.000) = 48 
    [30.000, 32.500) = 51 
    [32.500, 35.000) = 6 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.104 ms/op
     p(50.0000) =      3.764 ms/op
     p(90.0000) =      4.489 ms/op
     p(95.0000) =      4.948 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     23.865 ms/op
     p(99.9900) =     31.523 ms/op
     p(99.9990) =     32.957 ms/op
     p(99.9999) =     34.406 ms/op
    p(100.0000) =     34.406 ms/op


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
# Warmup Iteration   1: 11.163 ±(99.9%) 0.142 ms/op
# Warmup Iteration   2: 4.381 ±(99.9%) 0.019 ms/op
# Warmup Iteration   3: 3.998 ±(99.9%) 0.012 ms/op
Iteration   1: 3.835 ±(99.9%) 0.011 ms/op
                 existUser·p0.00:   1.325 ms/op
                 existUser·p0.50:   3.690 ms/op
                 existUser·p0.90:   4.301 ms/op
                 existUser·p0.95:   4.882 ms/op
                 existUser·p0.99:   6.382 ms/op
                 existUser·p0.999:  22.630 ms/op
                 existUser·p0.9999: 26.640 ms/op
                 existUser·p1.00:   27.984 ms/op

Iteration   2: 3.949 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   2.294 ms/op
                 existUser·p0.50:   3.785 ms/op
                 existUser·p0.90:   4.645 ms/op
                 existUser·p0.95:   5.120 ms/op
                 existUser·p0.99:   7.012 ms/op
                 existUser·p0.999:  12.915 ms/op
                 existUser·p0.9999: 27.754 ms/op
                 existUser·p1.00:   28.606 ms/op

Iteration   3: 3.831 ±(99.9%) 0.014 ms/op
                 existUser·p0.00:   1.192 ms/op
                 existUser·p0.50:   3.678 ms/op
                 existUser·p0.90:   4.125 ms/op
                 existUser·p0.95:   4.737 ms/op
                 existUser·p0.99:   8.036 ms/op
                 existUser·p0.999:  26.968 ms/op
                 existUser·p0.9999: 32.602 ms/op
                 existUser·p1.00:   35.717 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 247884
  mean =      3.871 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 269 
    [ 2.500,  5.000) = 235412 
    [ 5.000,  7.500) = 10018 
    [ 7.500, 10.000) = 1515 
    [10.000, 12.500) = 382 
    [12.500, 15.000) = 16 
    [15.000, 17.500) = 16 
    [17.500, 20.000) = 0 
    [20.000, 22.500) = 9 
    [22.500, 25.000) = 24 
    [25.000, 27.500) = 124 
    [27.500, 30.000) = 60 
    [30.000, 32.500) = 30 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 1 

  Percentiles, ms/op:
      p(0.0000) =      1.192 ms/op
     p(50.0000) =      3.723 ms/op
     p(90.0000) =      4.424 ms/op
     p(95.0000) =      4.981 ms/op
     p(99.0000) =      7.225 ms/op
     p(99.9000) =     22.367 ms/op
     p(99.9900) =     31.137 ms/op
     p(99.9990) =     34.509 ms/op
     p(99.9999) =     35.717 ms/op
    p(100.0000) =     35.717 ms/op


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
# Warmup Iteration   1: 14.011 ±(99.9%) 0.198 ms/op
# Warmup Iteration   2: 5.045 ±(99.9%) 0.029 ms/op
# Warmup Iteration   3: 3.917 ±(99.9%) 0.010 ms/op
Iteration   1: 4.208 ±(99.9%) 0.017 ms/op
                 getUser·p0.00:   1.985 ms/op
                 getUser·p0.50:   3.920 ms/op
                 getUser·p0.90:   4.964 ms/op
                 getUser·p0.95:   6.078 ms/op
                 getUser·p0.99:   8.552 ms/op
                 getUser·p0.999:  22.479 ms/op
                 getUser·p0.9999: 40.567 ms/op
                 getUser·p1.00:   40.894 ms/op

Iteration   2: 4.024 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.411 ms/op
                 getUser·p0.50:   3.908 ms/op
                 getUser·p0.90:   4.557 ms/op
                 getUser·p0.95:   5.128 ms/op
                 getUser·p0.99:   7.309 ms/op
                 getUser·p0.999:  12.517 ms/op
                 getUser·p0.9999: 25.334 ms/op
                 getUser·p1.00:   27.132 ms/op

Iteration   3: 3.951 ±(99.9%) 0.010 ms/op
                 getUser·p0.00:   2.261 ms/op
                 getUser·p0.50:   3.842 ms/op
                 getUser·p0.90:   4.325 ms/op
                 getUser·p0.95:   4.514 ms/op
                 getUser·p0.99:   6.586 ms/op
                 getUser·p0.999:  23.859 ms/op
                 getUser·p0.9999: 26.280 ms/op
                 getUser·p1.00:   26.771 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 236640
  mean =      4.058 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  5.000) = 223069 
    [ 5.000, 10.000) = 12756 
    [10.000, 15.000) = 497 
    [15.000, 20.000) = 42 
    [20.000, 25.000) = 184 
    [25.000, 30.000) = 60 
    [30.000, 35.000) = 0 
    [35.000, 40.000) = 14 
    [40.000, 45.000) = 18 

  Percentiles, ms/op:
      p(0.0000) =      1.411 ms/op
     p(50.0000) =      3.899 ms/op
     p(90.0000) =      4.628 ms/op
     p(95.0000) =      5.128 ms/op
     p(99.0000) =      7.496 ms/op
     p(99.9000) =     22.479 ms/op
     p(99.9900) =     39.671 ms/op
     p(99.9990) =     40.763 ms/op
     p(99.9999) =     40.894 ms/op
    p(100.0000) =     40.894 ms/op


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
# Warmup Iteration   1: 13.125 ±(99.9%) 0.204 ms/op
# Warmup Iteration   2: 5.721 ±(99.9%) 0.032 ms/op
# Warmup Iteration   3: 5.012 ±(99.9%) 0.019 ms/op
Iteration   1: 4.695 ±(99.9%) 0.017 ms/op
                 listUser·p0.00:   1.634 ms/op
                 listUser·p0.50:   4.415 ms/op
                 listUser·p0.90:   5.136 ms/op
                 listUser·p0.95:   6.349 ms/op
                 listUser·p0.99:   9.502 ms/op
                 listUser·p0.999:  24.347 ms/op
                 listUser·p0.9999: 26.307 ms/op
                 listUser·p1.00:   27.427 ms/op

Iteration   2: 4.498 ±(99.9%) 0.010 ms/op
                 listUser·p0.00:   2.281 ms/op
                 listUser·p0.50:   4.407 ms/op
                 listUser·p0.90:   4.858 ms/op
                 listUser·p0.95:   5.095 ms/op
                 listUser·p0.99:   7.770 ms/op
                 listUser·p0.999:  17.203 ms/op
                 listUser·p0.9999: 23.429 ms/op
                 listUser·p1.00:   24.576 ms/op

Iteration   3: 4.834 ±(99.9%) 0.014 ms/op
                 listUser·p0.00:   2.527 ms/op
                 listUser·p0.50:   4.645 ms/op
                 listUser·p0.90:   5.317 ms/op
                 listUser·p0.95:   6.253 ms/op
                 listUser·p0.99:   9.028 ms/op
                 listUser·p0.999:  18.413 ms/op
                 listUser·p0.9999: 23.626 ms/op
                 listUser·p1.00:   24.740 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 205349
  mean =      4.672 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 10 
    [ 2.500,  5.000) = 177637 
    [ 5.000,  7.500) = 22606 
    [ 7.500, 10.000) = 4075 
    [10.000, 12.500) = 409 
    [12.500, 15.000) = 126 
    [15.000, 17.500) = 180 
    [17.500, 20.000) = 70 
    [20.000, 22.500) = 39 
    [22.500, 25.000) = 163 
    [25.000, 27.500) = 34 

  Percentiles, ms/op:
      p(0.0000) =      1.634 ms/op
     p(50.0000) =      4.456 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.693 ms/op
     p(99.0000) =      8.962 ms/op
     p(99.9000) =     22.217 ms/op
     p(99.9900) =     25.592 ms/op
     p(99.9990) =     27.256 ms/op
     p(99.9999) =     27.427 ms/op
    p(100.0000) =     27.427 ms/op


# Run complete. Total time: 00:13:11

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.720 ± 4.215  ops/ms
ClientPb.existUser                       thrpt       3   8.544 ± 1.640  ops/ms
ClientPb.getUser                         thrpt       3   7.943 ± 1.659  ops/ms
ClientPb.listUser                        thrpt       3   6.870 ± 2.264  ops/ms
ClientPb.createUser                       avgt       3   4.033 ± 1.271   ms/op
ClientPb.existUser                        avgt       3   3.820 ± 1.479   ms/op
ClientPb.getUser                          avgt       3   3.960 ± 0.703   ms/op
ClientPb.listUser                         avgt       3   4.607 ± 1.436   ms/op
ClientPb.createUser                     sample  245699   3.908 ± 0.007   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.104           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.764           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.489           ms/op
ClientPb.createUser:createUser·p0.95    sample           4.948           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          23.865           ms/op
ClientPb.createUser:createUser·p0.9999  sample          31.523           ms/op
ClientPb.createUser:createUser·p1.00    sample          34.406           ms/op
ClientPb.existUser                      sample  247884   3.871 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.192           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.723           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.424           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.981           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.225           ms/op
ClientPb.existUser:existUser·p0.999     sample          22.367           ms/op
ClientPb.existUser:existUser·p0.9999    sample          31.137           ms/op
ClientPb.existUser:existUser·p1.00      sample          35.717           ms/op
ClientPb.getUser                        sample  236640   4.058 ± 0.007   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.411           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.899           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.628           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.128           ms/op
ClientPb.getUser:getUser·p0.99          sample           7.496           ms/op
ClientPb.getUser:getUser·p0.999         sample          22.479           ms/op
ClientPb.getUser:getUser·p0.9999        sample          39.671           ms/op
ClientPb.getUser:getUser·p1.00          sample          40.894           ms/op
ClientPb.listUser                       sample  205349   4.672 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.634           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.456           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.693           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.962           ms/op
ClientPb.listUser:listUser·p0.999       sample          22.217           ms/op
ClientPb.listUser:listUser·p0.9999      sample          25.592           ms/op
ClientPb.listUser:listUser·p1.00        sample          27.427           ms/op
