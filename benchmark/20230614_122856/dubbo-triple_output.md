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
# Warmup Iteration   1: 1.599 ops/ms
# Warmup Iteration   2: 3.591 ops/ms
# Warmup Iteration   3: 7.257 ops/ms
Iteration   1: 7.144 ops/ms
Iteration   2: 7.988 ops/ms
Iteration   3: 7.686 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  7.606 ±(99.9%) 7.802 ops/ms [Average]
  (min, avg, max) = (7.144, 7.606, 7.988), stdev = 0.428
  CI (99.9%): [≈ 0, 15.408] (assumes normal distribution)


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
# Warmup Iteration   1: 1.873 ops/ms
# Warmup Iteration   2: 6.305 ops/ms
# Warmup Iteration   3: 8.082 ops/ms
Iteration   1: 8.150 ops/ms
Iteration   2: 8.480 ops/ms
Iteration   3: 8.679 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  8.436 ±(99.9%) 4.880 ops/ms [Average]
  (min, avg, max) = (8.150, 8.436, 8.679), stdev = 0.267
  CI (99.9%): [3.557, 13.316] (assumes normal distribution)


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
# Warmup Iteration   1: 2.210 ops/ms
# Warmup Iteration   2: 6.596 ops/ms
# Warmup Iteration   3: 7.471 ops/ms
Iteration   1: 8.172 ops/ms
Iteration   2: 7.734 ops/ms
Iteration   3: 7.672 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  7.859 ±(99.9%) 4.972 ops/ms [Average]
  (min, avg, max) = (7.672, 7.859, 8.172), stdev = 0.273
  CI (99.9%): [2.887, 12.831] (assumes normal distribution)


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
# Warmup Iteration   1: 2.066 ops/ms
# Warmup Iteration   2: 5.517 ops/ms
# Warmup Iteration   3: 6.326 ops/ms
Iteration   1: 6.620 ops/ms
Iteration   2: 6.798 ops/ms
Iteration   3: 6.988 ops/ms


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  6.802 ±(99.9%) 3.351 ops/ms [Average]
  (min, avg, max) = (6.620, 6.802, 6.988), stdev = 0.184
  CI (99.9%): [3.451, 10.153] (assumes normal distribution)


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

# Run progress: 33.33% complete, ETA 00:08:53
# Fork: 1 of 1
# Warmup Iteration   1: 14.963 ±(99.9%) 0.080 ms/op
# Warmup Iteration   2: 4.949 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 4.291 ±(99.9%) 0.007 ms/op
Iteration   1: 3.910 ±(99.9%) 0.012 ms/op
Iteration   2: 3.972 ±(99.9%) 0.011 ms/op
Iteration   3: 4.036 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  3.972 ±(99.9%) 1.147 ms/op [Average]
  (min, avg, max) = (3.910, 3.972, 4.036), stdev = 0.063
  CI (99.9%): [2.825, 5.120] (assumes normal distribution)


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

# Run progress: 41.67% complete, ETA 00:07:46
# Fork: 1 of 1
# Warmup Iteration   1: 12.359 ±(99.9%) 0.042 ms/op
# Warmup Iteration   2: 4.420 ±(99.9%) 0.007 ms/op
# Warmup Iteration   3: 3.794 ±(99.9%) 0.004 ms/op
Iteration   1: 3.854 ±(99.9%) 0.008 ms/op
Iteration   2: 3.841 ±(99.9%) 0.009 ms/op
Iteration   3: 3.797 ±(99.9%) 0.003 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  3.831 ±(99.9%) 0.539 ms/op [Average]
  (min, avg, max) = (3.797, 3.831, 3.854), stdev = 0.030
  CI (99.9%): [3.292, 4.370] (assumes normal distribution)


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
# Warmup Iteration   1: 12.173 ±(99.9%) 0.040 ms/op
# Warmup Iteration   2: 4.361 ±(99.9%) 0.004 ms/op
# Warmup Iteration   3: 4.098 ±(99.9%) 0.004 ms/op
Iteration   1: 3.999 ±(99.9%) 0.008 ms/op
Iteration   2: 4.011 ±(99.9%) 0.008 ms/op
Iteration   3: 3.837 ±(99.9%) 0.011 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  3.949 ±(99.9%) 1.776 ms/op [Average]
  (min, avg, max) = (3.837, 3.949, 4.011), stdev = 0.097
  CI (99.9%): [2.173, 5.725] (assumes normal distribution)


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
# Warmup Iteration   1: 13.902 ±(99.9%) 0.069 ms/op
# Warmup Iteration   2: 5.863 ±(99.9%) 0.014 ms/op
# Warmup Iteration   3: 5.044 ±(99.9%) 0.006 ms/op
Iteration   1: 4.618 ±(99.9%) 0.015 ms/op
Iteration   2: 4.683 ±(99.9%) 0.024 ms/op
Iteration   3: 4.731 ±(99.9%) 0.012 ms/op


Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  4.677 ±(99.9%) 1.033 ms/op [Average]
  (min, avg, max) = (4.618, 4.677, 4.731), stdev = 0.057
  CI (99.9%): [3.644, 5.710] (assumes normal distribution)


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
# Warmup Iteration   1: 12.282 ±(99.9%) 0.169 ms/op
# Warmup Iteration   2: 4.812 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.260 ±(99.9%) 0.017 ms/op
Iteration   1: 4.113 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.606 ms/op
                 createUser·p0.50:   3.928 ms/op
                 createUser·p0.90:   4.735 ms/op
                 createUser·p0.95:   5.128 ms/op
                 createUser·p0.99:   7.684 ms/op
                 createUser·p0.999:  24.459 ms/op
                 createUser·p0.9999: 31.861 ms/op
                 createUser·p1.00:   32.702 ms/op

Iteration   2: 3.874 ±(99.9%) 0.011 ms/op
                 createUser·p0.00:   1.323 ms/op
                 createUser·p0.50:   3.789 ms/op
                 createUser·p0.90:   4.301 ms/op
                 createUser·p0.95:   4.645 ms/op
                 createUser·p0.99:   6.201 ms/op
                 createUser·p0.999:  13.418 ms/op
                 createUser·p0.9999: 32.563 ms/op
                 createUser·p1.00:   33.292 ms/op

Iteration   3: 4.037 ±(99.9%) 0.014 ms/op
                 createUser·p0.00:   1.784 ms/op
                 createUser·p0.50:   3.764 ms/op
                 createUser·p0.90:   4.964 ms/op
                 createUser·p0.95:   5.775 ms/op
                 createUser·p0.99:   7.356 ms/op
                 createUser·p0.999:  28.141 ms/op
                 createUser·p0.9999: 32.017 ms/op
                 createUser·p1.00:   33.030 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.createUser":
  N = 239574
  mean =      4.006 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 370 
    [ 2.500,  5.000) = 224407 
    [ 5.000,  7.500) = 12847 
    [ 7.500, 10.000) = 1202 
    [10.000, 12.500) = 324 
    [12.500, 15.000) = 104 
    [15.000, 17.500) = 30 
    [17.500, 20.000) = 17 
    [20.000, 22.500) = 0 
    [22.500, 25.000) = 47 
    [25.000, 27.500) = 64 
    [27.500, 30.000) = 53 
    [30.000, 32.500) = 93 
    [32.500, 35.000) = 16 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.323 ms/op
     p(50.0000) =      3.805 ms/op
     p(90.0000) =      4.604 ms/op
     p(95.0000) =      5.308 ms/op
     p(99.0000) =      7.102 ms/op
     p(99.9000) =     24.393 ms/op
     p(99.9900) =     32.376 ms/op
     p(99.9990) =     33.214 ms/op
     p(99.9999) =     33.292 ms/op
    p(100.0000) =     33.292 ms/op


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
# Warmup Iteration   1: 13.189 ±(99.9%) 0.189 ms/op
# Warmup Iteration   2: 4.226 ±(99.9%) 0.017 ms/op
# Warmup Iteration   3: 4.129 ±(99.9%) 0.012 ms/op
Iteration   1: 3.980 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.430 ms/op
                 existUser·p0.50:   3.817 ms/op
                 existUser·p0.90:   4.497 ms/op
                 existUser·p0.95:   5.194 ms/op
                 existUser·p0.99:   7.602 ms/op
                 existUser·p0.999:  21.156 ms/op
                 existUser·p0.9999: 23.788 ms/op
                 existUser·p1.00:   25.494 ms/op

Iteration   2: 4.003 ±(99.9%) 0.012 ms/op
                 existUser·p0.00:   1.837 ms/op
                 existUser·p0.50:   3.875 ms/op
                 existUser·p0.90:   4.547 ms/op
                 existUser·p0.95:   5.202 ms/op
                 existUser·p0.99:   8.305 ms/op
                 existUser·p0.999:  12.517 ms/op
                 existUser·p0.9999: 27.099 ms/op
                 existUser·p1.00:   28.115 ms/op

Iteration   3: 3.810 ±(99.9%) 0.010 ms/op
                 existUser·p0.00:   2.021 ms/op
                 existUser·p0.50:   3.695 ms/op
                 existUser·p0.90:   4.178 ms/op
                 existUser·p0.95:   4.473 ms/op
                 existUser·p0.99:   6.447 ms/op
                 existUser·p0.999:  11.012 ms/op
                 existUser·p0.9999: 32.493 ms/op
                 existUser·p1.00:   33.554 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.existUser":
  N = 244346
  mean =      3.929 ±(99.9%) 0.007 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 217 
    [ 2.500,  5.000) = 232672 
    [ 5.000,  7.500) = 8943 
    [ 7.500, 10.000) = 1961 
    [10.000, 12.500) = 302 
    [12.500, 15.000) = 25 
    [15.000, 17.500) = 1 
    [17.500, 20.000) = 2 
    [20.000, 22.500) = 53 
    [22.500, 25.000) = 94 
    [25.000, 27.500) = 38 
    [27.500, 30.000) = 6 
    [30.000, 32.500) = 24 
    [32.500, 35.000) = 8 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.430 ms/op
     p(50.0000) =      3.781 ms/op
     p(90.0000) =      4.399 ms/op
     p(95.0000) =      4.923 ms/op
     p(99.0000) =      7.553 ms/op
     p(99.9000) =     12.534 ms/op
     p(99.9900) =     30.610 ms/op
     p(99.9990) =     33.129 ms/op
     p(99.9999) =     33.554 ms/op
    p(100.0000) =     33.554 ms/op


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
# Warmup Iteration   1: 13.442 ±(99.9%) 0.209 ms/op
# Warmup Iteration   2: 4.760 ±(99.9%) 0.024 ms/op
# Warmup Iteration   3: 4.408 ±(99.9%) 0.019 ms/op
Iteration   1: 4.163 ±(99.9%) 0.013 ms/op
                 getUser·p0.00:   1.937 ms/op
                 getUser·p0.50:   3.928 ms/op
                 getUser·p0.90:   4.841 ms/op
                 getUser·p0.95:   5.407 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  14.844 ms/op
                 getUser·p0.9999: 26.553 ms/op
                 getUser·p1.00:   27.722 ms/op

Iteration   2: 4.071 ±(99.9%) 0.014 ms/op
                 getUser·p0.00:   1.772 ms/op
                 getUser·p0.50:   3.809 ms/op
                 getUser·p0.90:   4.375 ms/op
                 getUser·p0.95:   6.390 ms/op
                 getUser·p0.99:   8.569 ms/op
                 getUser·p0.999:  19.530 ms/op
                 getUser·p0.9999: 27.661 ms/op
                 getUser·p1.00:   28.541 ms/op

Iteration   3: 3.845 ±(99.9%) 0.011 ms/op
                 getUser·p0.00:   1.194 ms/op
                 getUser·p0.50:   3.756 ms/op
                 getUser·p0.90:   4.149 ms/op
                 getUser·p0.95:   4.309 ms/op
                 getUser·p0.99:   5.464 ms/op
                 getUser·p0.999:  27.453 ms/op
                 getUser·p0.9999: 29.678 ms/op
                 getUser·p1.00:   30.573 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.getUser":
  N = 238540
  mean =      4.022 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 55 
    [ 2.500,  5.000) = 226242 
    [ 5.000,  7.500) = 7898 
    [ 7.500, 10.000) = 3322 
    [10.000, 12.500) = 651 
    [12.500, 15.000) = 106 
    [15.000, 17.500) = 7 
    [17.500, 20.000) = 28 
    [20.000, 22.500) = 6 
    [22.500, 25.000) = 45 
    [25.000, 27.500) = 92 
    [27.500, 30.000) = 85 
    [30.000, 32.500) = 3 
    [32.500, 35.000) = 0 
    [35.000, 37.500) = 0 

  Percentiles, ms/op:
      p(0.0000) =      1.194 ms/op
     p(50.0000) =      3.813 ms/op
     p(90.0000) =      4.497 ms/op
     p(95.0000) =      5.030 ms/op
     p(99.0000) =      8.290 ms/op
     p(99.9000) =     19.530 ms/op
     p(99.9900) =     29.164 ms/op
     p(99.9990) =     30.096 ms/op
     p(99.9999) =     30.573 ms/op
    p(100.0000) =     30.573 ms/op


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
# Warmup Iteration   1: 14.165 ±(99.9%) 0.211 ms/op
# Warmup Iteration   2: 5.195 ±(99.9%) 0.022 ms/op
# Warmup Iteration   3: 4.904 ±(99.9%) 0.019 ms/op
Iteration   1: 4.718 ±(99.9%) 0.016 ms/op
                 listUser·p0.00:   1.882 ms/op
                 listUser·p0.50:   4.604 ms/op
                 listUser·p0.90:   4.940 ms/op
                 listUser·p0.95:   5.661 ms/op
                 listUser·p0.99:   8.627 ms/op
                 listUser·p0.999:  24.936 ms/op
                 listUser·p0.9999: 26.645 ms/op
                 listUser·p1.00:   28.901 ms/op

Iteration   2: 4.676 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   1.702 ms/op
                 listUser·p0.50:   4.547 ms/op
                 listUser·p0.90:   5.161 ms/op
                 listUser·p0.95:   5.595 ms/op
                 listUser·p0.99:   8.398 ms/op
                 listUser·p0.999:  17.998 ms/op
                 listUser·p0.9999: 21.456 ms/op
                 listUser·p1.00:   23.331 ms/op

Iteration   3: 4.708 ±(99.9%) 0.012 ms/op
                 listUser·p0.00:   2.802 ms/op
                 listUser·p0.50:   4.555 ms/op
                 listUser·p0.90:   5.169 ms/op
                 listUser·p0.95:   5.513 ms/op
                 listUser·p0.99:   8.815 ms/op
                 listUser·p0.999:  16.354 ms/op
                 listUser·p0.9999: 19.242 ms/op
                 listUser·p1.00:   19.497 ms/op



Result "org.apache.dubbo.benchmark.ClientPb.listUser":
  N = 203924
  mean =      4.701 ±(99.9%) 0.008 ms/op

  Histogram, ms/op:
    [ 0.000,  2.500) = 11 
    [ 2.500,  5.000) = 178440 
    [ 5.000,  7.500) = 21721 
    [ 7.500, 10.000) = 2371 
    [10.000, 12.500) = 588 
    [12.500, 15.000) = 331 
    [15.000, 17.500) = 198 
    [17.500, 20.000) = 80 
    [20.000, 22.500) = 54 
    [22.500, 25.000) = 67 
    [25.000, 27.500) = 59 

  Percentiles, ms/op:
      p(0.0000) =      1.702 ms/op
     p(50.0000) =      4.571 ms/op
     p(90.0000) =      5.128 ms/op
     p(95.0000) =      5.579 ms/op
     p(99.0000) =      8.684 ms/op
     p(99.9000) =     19.399 ms/op
     p(99.9900) =     26.116 ms/op
     p(99.9990) =     28.385 ms/op
     p(99.9999) =     28.901 ms/op
    p(100.0000) =     28.901 ms/op


# Run complete. Total time: 00:13:18

REMEMBER: The numbers below are just data. To gain reusable insights, you need to follow up on
why the numbers are the way they are. Use profilers (see -prof, -lprof), design factorial
experiments, perform baseline and negative tests that provide experimental control, make sure
the benchmarking environment is safe on JVM/OS/HW level, ask for reviews from the domain experts.
Do not assume the numbers tell you what you want them to tell.

Benchmark                                 Mode     Cnt   Score   Error   Units
ClientPb.createUser                      thrpt       3   7.606 ± 7.802  ops/ms
ClientPb.existUser                       thrpt       3   8.436 ± 4.880  ops/ms
ClientPb.getUser                         thrpt       3   7.859 ± 4.972  ops/ms
ClientPb.listUser                        thrpt       3   6.802 ± 3.351  ops/ms
ClientPb.createUser                       avgt       3   3.972 ± 1.147   ms/op
ClientPb.existUser                        avgt       3   3.831 ± 0.539   ms/op
ClientPb.getUser                          avgt       3   3.949 ± 1.776   ms/op
ClientPb.listUser                         avgt       3   4.677 ± 1.033   ms/op
ClientPb.createUser                     sample  239574   4.006 ± 0.008   ms/op
ClientPb.createUser:createUser·p0.00    sample           1.323           ms/op
ClientPb.createUser:createUser·p0.50    sample           3.805           ms/op
ClientPb.createUser:createUser·p0.90    sample           4.604           ms/op
ClientPb.createUser:createUser·p0.95    sample           5.308           ms/op
ClientPb.createUser:createUser·p0.99    sample           7.102           ms/op
ClientPb.createUser:createUser·p0.999   sample          24.393           ms/op
ClientPb.createUser:createUser·p0.9999  sample          32.376           ms/op
ClientPb.createUser:createUser·p1.00    sample          33.292           ms/op
ClientPb.existUser                      sample  244346   3.929 ± 0.007   ms/op
ClientPb.existUser:existUser·p0.00      sample           1.430           ms/op
ClientPb.existUser:existUser·p0.50      sample           3.781           ms/op
ClientPb.existUser:existUser·p0.90      sample           4.399           ms/op
ClientPb.existUser:existUser·p0.95      sample           4.923           ms/op
ClientPb.existUser:existUser·p0.99      sample           7.553           ms/op
ClientPb.existUser:existUser·p0.999     sample          12.534           ms/op
ClientPb.existUser:existUser·p0.9999    sample          30.610           ms/op
ClientPb.existUser:existUser·p1.00      sample          33.554           ms/op
ClientPb.getUser                        sample  238540   4.022 ± 0.008   ms/op
ClientPb.getUser:getUser·p0.00          sample           1.194           ms/op
ClientPb.getUser:getUser·p0.50          sample           3.813           ms/op
ClientPb.getUser:getUser·p0.90          sample           4.497           ms/op
ClientPb.getUser:getUser·p0.95          sample           5.030           ms/op
ClientPb.getUser:getUser·p0.99          sample           8.290           ms/op
ClientPb.getUser:getUser·p0.999         sample          19.530           ms/op
ClientPb.getUser:getUser·p0.9999        sample          29.164           ms/op
ClientPb.getUser:getUser·p1.00          sample          30.573           ms/op
ClientPb.listUser                       sample  203924   4.701 ± 0.008   ms/op
ClientPb.listUser:listUser·p0.00        sample           1.702           ms/op
ClientPb.listUser:listUser·p0.50        sample           4.571           ms/op
ClientPb.listUser:listUser·p0.90        sample           5.128           ms/op
ClientPb.listUser:listUser·p0.95        sample           5.579           ms/op
ClientPb.listUser:listUser·p0.99        sample           8.684           ms/op
ClientPb.listUser:listUser·p0.999       sample          19.399           ms/op
ClientPb.listUser:listUser·p0.9999      sample          26.116           ms/op
ClientPb.listUser:listUser·p1.00        sample          28.901           ms/op
